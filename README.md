Object-oriented Programming refers to a type of computer programming in which developers define not only the data type of a data structure, but also the types of operations that can be applied to the data structure.

In this way, the data structure becomes an object that includes both data and functions. In addition, developers can create relationships between one object and another. For example, objects can inherit characteristics from other objects.
One of the principal advantages of object-oriented pattern over procedural pattern is that they enable developers to create modules that do not need to be changed when a new type of object is added. A developer can simply create a new object that inherits many of its features from existing objects. This makes object-oriented programs easier to modify.

Project: Favorite songs from a music app
Description
I propose a system where the user can see a list of songs in a music app, the user can see the details of each song, the genre, the artist and they can and be able to add songs to their own list of favorites.

User Stories
As a User I want to browse the available songs on Deezer/Spotify.
- see song details
- add a song to my favorites list.
- remove a song from my favorites list.
- see my list of favorites songs.



Pseudo Code

class User {
  user name,
  email,
  password
  favorites list of songs
  ---
  addFavorite()
  removeFavorite()
  getFavorites()
}

class Song {
  title,
  artist,
  genre,
  list of songs
  ---
  addSong()
  removeSong()
  getSongs()
}

user = create user('name', 'user@mail.com', 'pw')

song1 = create song('title 1', 'artist', 'rnb')
song2 = create song('title 2', 'artist', 'rock')

list of songs = [song1, song2]

user.addFavorite(song1)
user.addFavorite(song2)
user.removeFavorite(song1)

user.getFavorites()
