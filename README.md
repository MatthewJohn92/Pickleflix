# PickleFlix

PickleFlix is a school project that replicates the popular streaming platform Netflix, but with a unique twist: it hosts only cucumber videos! This project is developed using Next.js.

## Features

- **Cucumber Video Streaming**: Watch the best cucumber videos in high quality.
- **Intuitive User Interface**: Simple and Netflix-like interface for an optimal user experience.
- **Advanced Search**: Easily find your favorite cucumber videos.
- **Responsive Design**: Enjoy PickleFlix on any device, from desktop to mobile.

## Technologies Used

- **Next.js**: React framework for modern web application development.
- **React**: JavaScript library for building user interfaces.
- **CSS Modules**: For component styling.
- **Node.js**: JavaScript runtime environment for server-side development.
- **Express**: Web application framework for Node.js.
- **MongoDB**: NoSQL database for data management.
- **Prisma**: ORM to interface with MongoDB.
- **NextAuth.js**: Authentication solution for Next.js.

## Requirements

- Node.js version 14 or higher
- NPM version 6 or higher
- MongoDB

## Installation

1. Clone the repository:

    ```bash
    git clone https://github.com/MatthewJohn92/Pickleflix.git
    ```

2. Navigate to the project directory:

    ```bash
    cd pickleflix
    ```

3. Install the dependencies:

    ```bash
    npm install
    ```

4. Set up Prisma:

    ```bash
    npm install -D prisma
    npx prisma init
    npm install @prisma/client
    ```

5. Set up authentication:

    ```bash
    npm install next-auth
    ```

6. Install other necessary dependencies:

    ```bash
    npm install bcrypt
    npm install react-icons
    npm install swr
    ```

7. Start the application in development mode:

    ```bash
    npm run dev
    ```

8. Open [http://localhost:3000](http://localhost:3000) in your browser to see the application running.

## MongoDB Configuration

Make sure MongoDB is running. You can use a MongoDB hosting service like MongoDB Atlas or run MongoDB locally. Configure the `.env` file in the root of the project with your MongoDB connection URI:

# ITA

# PickleFlix

PickleFlix è un progetto scolastico che replica la popolare piattaforma di streaming Netflix, ma con una differenza unica: ospita solo video di cetrioli! Questo progetto è sviluppato utilizzando Next.js.

## Caratteristiche

- **Streaming di video di cetrioli**: Guarda i migliori video di cetrioli in alta qualità.
- **Interfaccia utente intuitiva**: Interfaccia semplice e simile a Netflix per un'esperienza utente ottimale.
- **Ricerca avanzata**: Trova i tuoi video di cetrioli preferiti con facilità.
- **Responsive design**: Goditi PickleFlix su qualsiasi dispositivo, dal desktop al mobile.

## Tecnologie Utilizzate

- **Next.js**: Framework React per lo sviluppo di applicazioni web moderne.
- **React**: Libreria JavaScript per la costruzione di interfacce utente.
- **CSS Modules**: Per lo styling dei componenti.
- **Node.js**: Ambiente di runtime JavaScript lato server.
- **Express**: Framework per applicazioni web Node.js.
- **MongoDB**: Database NoSQL per la gestione dei dati.
- **Prisma**: ORM per interfacciarsi con MongoDB.
- **NextAuth.js**: Soluzione per l'autenticazione in Next.js.

## Requisiti

- Node.js versione 14 o superiore
- NPM versione 6 o superiore
- MongoDB

## Installazione

1. Clona il repository:

    ```bash
    git clone https://github.com/MatthewJohn92/Pickleflix.git
    ```

2. Naviga nella directory del progetto:

    ```bash
    cd pickleflix
    ```

3. Installa le dipendenze:

    ```bash
    npm install
    ```

4. Configura Prisma:

    ```bash
    npm install -D prisma
    npx prisma init
    npm install @prisma/client
    ```

5. Configura l'autenticazione:

    ```bash
    npm install next-auth
    ```

6. Installa altre dipendenze necessarie:

    ```bash
    npm install bcrypt
    npm install react-icons
    npm install swr
    ```

7. Avvia l'applicazione in modalità di sviluppo:

    ```bash
    npm run dev
    ```

8. Apri [http://localhost:3000](http://localhost:3000) nel tuo browser per vedere l'applicazione in esecuzione.

## Configurazione di MongoDB

Assicurati di avere MongoDB in esecuzione. Puoi utilizzare un servizio di hosting di MongoDB come MongoDB Atlas oppure eseguire MongoDB localmente. Configura il file `.env` nella radice del progetto con il tuo URI di connessione a MongoDB:

```env
DATABASE_URL="mongodb+srv://<username>:<password>@cluster0.mongodb.net/<yourcluster>"
