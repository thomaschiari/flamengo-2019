# React + TypeScript + Vite

## Project Structure

### Folder Structure:
src
├── assets
│   ├── images
│   └── icons
├── components
├── context
├── pages
├── services
├── store
├── types
├── util
└── test

### Descriptions:

- `assets`: Used to store lightweight images (for heavy images, prefer using a CDN), icons, etc.
- `components`: Reusable components of the application. These are units for your application, like buttons, modals, etc.
- `context`: Maintains all the contexts of the application.
- `pages`: The pages are what the user will see and where the components will be sumarized
- `services`: Contains the configurations for HTTP clients and connections for API's.
- `store`: Holds the definitions for state managers, context API, zustand, redux.
- `types`: Stores TypeScript typings (types and interfaces) that are common across various parts of the project.
- `utils`: Utility functions such as formatCurrency, formatPhone, convertTimezone, parsePhone, etc. (pure JavaScript).
- `test`:  Contains the setup for tests.


## Progress

- [x] Setup with all the folders (organized)
- [x] Implement Routes General
- [x] Implement Routes User
- [x] Basic Page Login in Routes User (login)
- [x] Connect to Zambom's API
- [x] Save the token in local storage
- [x] Implement React Redux
- [x] Implement data from Zambom's API in React Redux
- [ ] Add Persistance in react redux
- [ ] Connect to Palmeiras's API (our backend)
- [ ] Page List of rentals
- [ ] Page List of rentals: add filters
- [ ] Page New Rental
- [ ] Validation in forms
