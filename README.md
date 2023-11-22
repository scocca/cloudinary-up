# cloudinary-up
cloudinary single upload implementation

implementacion de carga de imagen unica a cloudinary

npm init -y
npm install express cloudinary dotenv multer multer-storage-cloudinary
npm install -D nodemon

  "scripts": {
    "dev": "nodemon index.js",
    "start": "node index.js"
  },

  .env:
  CLOUD_NAME=completar
  CLOUDINARY_KEY=completar
  CLOUDINARY_SECRET=completar

  para probar:

  enviar solicitud POST
  http://localhost:8083/upload
  body->form-data->key:image type:File

  las imagenes se cargaran al directorio: CloudinaryDemo en cloudinary
  
  Fuente: https://dev.to/evansitworld/upload-images-with-nodejs-and-express-to-the-cloud-using-cloudinary-26e4

  
