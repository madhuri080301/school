
### Getting Started

Go to the root folder and install the backend dependencies by using the command-

```bash
npm install
```

Go to the frontend folder by command cd frontend and then install frontend dependecies using the command-

```bash
npm install
```

### `ENV Variables`

Create a .env file in the root and add the following

```bash
NODE_ENV=development
PORT=5000
MONGO_URI="Your mongo uri"
JWT_SECRET="Anything you like"
CLOUDINARY_URL ="your cloudinary url"
CLOUDINARY_UPLOAD_PRESET = "your cloudinary preset "
```

### `Running`

```bash
Go to the root folder
npm run dev
