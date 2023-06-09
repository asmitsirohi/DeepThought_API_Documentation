# API Documentation

This api is for the demo purpose. This api can give you the dummy data which is fetched from third party server.

### We provide you the data of different category:

- Posts
- Users
- Comments
- Albums
- Photos
- Todos

# Request URL

**Base URL:** http://localhost:5000/api/${type}

## API Reference

#### Get Posts

```http
  GET /api/posts
```

| Parameter | Type     | Description                         |
| :-------- | :------- | :---------------------------------- |
| `type`    | `string` | **Required**. Type of data to fetch |

#### Get Users

```http
  GET /api/users
```

| Parameter | Type     | Description                         |
| :-------- | :------- | :---------------------------------- |
| `type`    | `string` | **Required**. Type of data to fetch |

#### Get Comments

```http
  GET /api/comments
```

| Parameter | Type     | Description                         |
| :-------- | :------- | :---------------------------------- |
| `type`    | `string` | **Required**. Type of data to fetch |

#### Get Albums

```http
  GET /api/albums
```

| Parameter | Type     | Description                         |
| :-------- | :------- | :---------------------------------- |
| `type`    | `string` | **Required**. Type of data to fetch |

#### Get Photos

```http
  GET /api/photos
```

| Parameter | Type     | Description                         |
| :-------- | :------- | :---------------------------------- |
| `type`    | `string` | **Required**. Type of data to fetch |

#### Get Todos

```http
  GET /api/todos
```

| Parameter | Type     | Description                         |
| :-------- | :------- | :---------------------------------- |
| `type`    | `string` | **Required**. Type of data to fetch |

## Appendix

**API Source Code:** [DeepThought_API](https://github.com/asmitsirohi/DeepThought_API)
