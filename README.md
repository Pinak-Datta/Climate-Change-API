
# Climate Change API
[![MIT License](https://img.shields.io/apm/l/atomic-design-ui.svg?)](https://github.com/tterb/atomic-design-ui/blob/master/LICENSEs)


A Climate Change API that fetches all the news across the globe on the topic of "Climate Change" .


You can check and use the API from here :  
[API Link](https://rapidapi.com/pinakdatta2002/api/live-climate-change12)

## API Reference

#### Fetch News from all newspapers : 

```http
  GET /api/news
```

| Parameter | Type     | Description                |
| :-------- | :------- | :------------------------- |
| `api_key` | `string` | (**Required**) Your Personal API key |

#### Get news from a particular newspaper

```http
  GET /api/news/${newspaperId}
```

| Parameter | Type     | Description                       |
| :-------- | :------- | :-------------------------------- |
| `newspaperId`      | `string` | (**Required**) Id of the newspaper of which you want the result |






## Deployment

To use  this API , check out the link given above, and get your own API_KEY.

The `documentation` on using the API is given in that website.


## Contributing to this Repo

Contributions are always welcome!

See `contributing.md` for ways to get started.

Please adhere to this project's `code of conduct`.


## License

[MIT](https://choosealicense.com/licenses/mit/)

