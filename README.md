# B.O.A.B | Ballin' On a Budget
Save Smart is a one stop shop for organizing all your budgeting needs. This application is is designed to help you visualize your spending, and get a better understanding of where your dollar is going.

## Links
- Client Application:
- API:
- Front-End Repository:

## Technologies Used
#### Front-End:
- React.js
- Node.js
- Bootstrap

#### Back-End:
- Express.js
- Axios
- MongoDB
- Mongoose

## Entity Relationship Diagram
![ERD]

## API End Points
| Verb   | URI Pattern               | Controller#Action |
|--------|---------------------------|-------------------|
| POST   | `/sign-up`                | `users#signup`    |
| POST   | `/sign-in`                | `users#signin`    |
| DELETE | `/sign-out`               | `users#signout`   |
| PATCH  | `/change-password`        | `users#changepw`  |
| GET    | `/expenses`               | `expenses#index`  |
| GET    | `/expenses`               |  `expenses#show`  |
| PATCH  | `/expenses`               | `expenses#update` |
| POST   | `/expenses`               | `expenses#create` |
| DELETE | `/expenses`               | `expenses#destroy`|

## Next Steps
- The next step would be to move beyond just expenses, and incorprate income and savings information into the dashboard.

## Setup Steps
