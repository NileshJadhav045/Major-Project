
# Wanderlust (In Progress)

Wanderlust is a full-stack travel accommodation listing web application (similar to Airbnb or YelpCamp). Users can browse, create, edit, and delete listings. This is a work-in-progress project built using Node.js, Express, MongoDB, and EJS.

---

## Project Status

 **Current Features:**

- View all listings in a card-based layout  
- Add, edit, and delete listings  
- Listing details with dynamic routes  
- Modularized EJS views using layouts/includes  
- Sample listings seeding via script  
- Basic styling with Bootstrap 5 and custom CSS  

 **Upcoming Features:**

- User authentication (Passport.js)  
- Flash messages & error handling  
- Image upload via Cloudinary  
- Maps integration using Mapbox  
- Reviews & comments system  

---

## Tech Stack

| Tech           | Use                            |
|----------------|---------------------------------|
| Node.js        | JavaScript runtime              |
| Express.js     | Web framework                   |
| MongoDB        | NoSQL database                  |
| Mongoose       | MongoDB ODM                     |
| EJS            | Templating engine               |
| Bootstrap 5    | Frontend styling framework      |
| FontAwesome    | Icons                           |

---

## Project Structure

```
wanderlust/
├── views/
│   ├── listings/          # index, new, edit, show
│   ├── includes/          # navbar, footer
│   └── layouts/           # boilerplate.ejs
├── public/
│   └── CSS/style.css      # Custom styles
├── models/listing.js      # Mongoose schema
├── data.js                # Sample listings
├── index.js               # DB seeding script
```

---


## Screens (coming soon)

- Listings homepage
- Add/Edit forms
- Detail view page

---

## Author

**Nilesh Jadhav**  
[GitHub](https://github.com/NileshJadhav045)  
[nileshjadhav01776@gamil.com]

---


##  Notes

- Project is under active development.
- Contributions or suggestions are welcome!
