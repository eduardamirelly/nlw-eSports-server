![cover](.github/cover.jpg?style=flat)

<p align="center">
  <img alt="License" src="https://img.shields.io/static/v1?label=license&message=MIT&color=8257E5&labelColor=0A1033">
  <img src="https://img.shields.io/static/v1?label=NLW&message=eSports&color=8257E5&labelColor=0A1033" alt="NLW eSports" />
</p>

## 💻 Project [Server]

API of games and users ads about duos on games.

## ✨ Technologies

- [ ] Express
- [ ] Nodemon
- [ ] Cors
- [ ] Prisma
- [ ] Typescript

## 🔖 Layout

You can view the project layout through [this link](https://www.figma.com/community/file/1150897317533332617).

## Running the project

### Firt Step [Install dependencies]

On ./nlw-eSports-server directory

```cl
npm install
```

### Second Step [Prisma Setup]

On ./nlw-eSports-server directory:

```cl
npx prisma init --datasource-provider SQLite
```

And run the migrates:

```cl
npx prisma migrate dev
```

You can set the database local on the same directory I save, if you want:

```cl
DATABASE_URL="file:../src/database/db.sqlite"
```

### Last Step [Run]

For finally run this project:

On ./nlw-eSports-server for run expo:

```ci
npm run dev
```

You can use this API to feed this others projects.

- [nlw-eSports-web](https://github.com/eduardamirelly/nlw-eSports-web)
- [nlw-eSports-mobile](https://github.com/eduardamirelly/nlw-eSports-mobile)

## 📄 License

This project is under the MIT license. See the [LICENSE](LICENSE) file for more details.
