# Drakor API

<p align="center">
<img alt="GitHub issues" src="https://img.shields.io/github/issues/Kaede-No-Ki/drakor-rest-api">
<img alt="GitHub pull requests" src="https://img.shields.io/github/issues-pr/Kaede-No-Ki/drakor-rest-api">
<img alt="GitHub" src="https://img.shields.io/github/license/Kaede-No-Ki/drakor-rest-api"> 
<img alt="GitHub stars" src="https://img.shields.io/github/stars/Kaede-No-Ki/drakor-rest-api">
<img alt="GitHub forks" src="https://img.shields.io/github/forks/Kaede-No-Ki/drakor-rest-api">
<img alt="GitHub watchers" src="https://img.shields.io/github/watchers/Kaede-No-Ki/drakor-rest-api">
<img alt="GitHub contributors" src="https://img.shields.io/github/contributors/Kaede-No-Ki/drakor-rest-api">
<img alt="GitHub last commit" src="https://img.shields.io/github/last-commit/Kaede-No-Ki/drakor-rest-api">
</p>

## TODO

- [x] Home
- [x] List Drakor
- [x] Detail Drakor
- [x] Episode Drakor
- [ ] List Korean Movie
- [ ] Detail Korean Movie
- [ ] Search
- [ ] Genre
- [ ] OnGoing
- [ ] Complete

## Usage

1. Clone this repository

```bash
git clone https://github.com/Kaede-No-Ki/drakor-rest-api.git
```

2. Install packages (use `yarn` or `npm`)

```bash
npm install
```

3. Start server

- a. Production

```bash
npm run start
```

- b. Development

```bash
npm run dev
```

## API Documentation

**API Version** : v1

| Endpoint           | Params      | Description    |
| ------------------ | ----------- | -------------- |
| /                  | -           | Homepage       |
| /list/:page        | page : Int  | List Drakor    |
| /detail/series/:id | id : String | Detail Drakor  |
| /episode/:id       | id : String | Detail Episode |

## Contributing

Pull requests are welcome. For major changes, please open an issue first to discuss what you would like to change.

Please make sure to update tests as appropriate.