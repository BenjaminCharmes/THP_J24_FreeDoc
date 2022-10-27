<h1 align="center">Day 24 of The Hacking Project: Relationship between databases</h1>

Here is exercise 1 in Ruby on Rails from day 23 of The Hacking Project: FreeDoc - Book your `doctor` !

<h2 align="center">🎉 Day 9 of the Full Stack training 🎉</h2>

### Models & Tables

- `Doctors` 
  - `first_name`
  - `last_name`
  - `zip_code`

- `Specialties` 
  - `specialty`

- `DoctorSpecialties` 

1. A `doctor` would have several `specialties` (DEAL_WITH_IT), and a `specialty` could involve several `doctors`.

- `Patients`
  - `first_name`
  - `last_name`

- `Appointments`
  - `date`

1. An `appointment` can only have one `doctor`, but a `doctor` can have several `appointments`.

2. An `appointment` can only have one `patient`, but a `patient` can have several `appointments`.

3. A `doctor` can have several `patient`s, through `appointments`, and vice versa.

- `Cities`
  - `name`

1. A `city` can have several `doctors`, `patients`, and `appointments`.


