# Flatnote

Flatnote is a note-taking app that allows users to easily filter notes by multiple tags.

[Full Demo](https://www.youtube.com/watch?v=reKIlvSAIFo&feature=youtu.be)

![Flatnote demo](https://j.gifs.com/YWJMM9.gif)

I implemented user authentication and authorization by integrating JSON Web Tokens and BCrypt with localStorage.

I built the front end using React with Redux, React Router, and React Bootstrap.

I built the API using Rails with PostgreSQL and ActiveRecord.

## Installing Flatnote

To install Flatnote, follow these steps:

1. Clone the full contents of this repo and its submodules

```
git clone --recurse-submodules git@github.com:mpottebaum/flatnote.git
```

2. Install gems in the back end directory:

```
cd flatnote-backend
bundle
```

2. Install dependencies in the front end directory:

```
cd flatnote-frontend
npm install
```

## Using Flatnote

To use Flatnote, follow these steps:

1. From the flatnote-backend directory, start the API server. Make sure the API server is running on `localhost:3000`.

```
rails s
```

2. From the flatnote-frontend directory, start the front end server.

```
npm start
```

The front end server should automatically run on `localhost:3001`, but any port will work.

## Contact

If you want to contact me you can reach me at mpottebaum@gmail.com.