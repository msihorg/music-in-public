# Music In Public
A program, to provide charitable and educational assistance to musicians playing acoustic music in public spaces, of Make Sure It Happens Inc, a Maryland non-profit and 501(c)(3) EIN 85-3536160 | www.msih.org | ithappens@msih.org | 717-674-4674

# Purpose
- A React project to provide information about playing music in public spaces: rules, processes, players, regulations, laws, court cases, and history. 
- A musician, band, or manager schedule public performance
- A venue requesting music to be played: compensated and uncompensated
- An organization requesting music to be played: compensated and uncompensated
- Calendar of events and add to user's calendar

## Technology
- Frontend: React
- CCS Framework: tailwind
- Backend: MySQL
- Map: Google (autocomplete)
- Email Providers: SendGrid or AWS
- Payment Gateway: Braintree (Paypal)
- Analytics: Facebook, Google
- Unit Testing: xUnit

## Model
- users
- musicians (students, hobby, professional)
- bands (high school, college, hobby, professional)
- managers (manage professional bands)
- bookers (create and schedule events)
- sponsors (donate to pay musicians)
- venues (parks, other public places, private places (hotel lobby)
- events (venue, date/time, duration)
- localities (state, county, city, federal)
- regulations (laws, rules, and permits)
- instruments
- music styles

## Use Cases
- sign up as a musician
- sign up as a booker
- sign up as a manager
- sign up sponsors (pay for music)

### Schedule Music
- musician creates profile: instrument and style ...
- musician creates a band and then invites other musicians into the band, other musicians accept the invite
- booker creates a venue
- booker creates an event by specifying a venue, start and end date/time
- musician creates an event by specifying a venue, start and end date/time
- manager can invite musician or band to be managed
- musician can invite a manager to be their manager
- sponsor can create an event
- sponsor can sponsor an existing event
- events can be reoccurring

### Information
- booker creates regulations for venue or locality

## Project Plan

### Phase 1 - MVP

- user management: sign up (screen), log in (passwordless), log off
- Landing page (screen)
- Search results screen
- Profile screen
- Footer
- Menu  

### Phase 2

- google autocomplete
- better search capabilities
