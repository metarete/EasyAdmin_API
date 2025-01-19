
# EasyAdmin API

> ⚠️ **Warning**: This is a work-in-progress, the project isn't finished yet... Be cautious while proceeding!

EasyAdmin API is a test project to implement an EasyAdmin and Symfony-based frontend and an API Platform Symfony backend.

The backend uses a MySQL database, and the EA frontend implements CRUD operations via REST API, without a local database.

The EA stuff are based on the great post [Managing Virtual Entities in Symfony’s EasyAdmin Without Doctrine Persistence](https://medium.com/@maurice2k5/managing-virtual-entities-in-symfonys-easyadmin-without-doctrine-persistence-2271c3711c41) by Maurice Bennett 👏


## Features

- backend
  - docker setup (PHP-FPM, apache, MySQL database)
  - API platform 
  - RESTful API (no authentication, 2 related entities)
- web frontend
  - docker setup (PHP-FPM, apache)
  - EasyAdmin CRUD admin interface (no authentication)


## Usage

TODO

### Start backend

The API will be available at `http://localhost:8080/api`.

### Start frontend

The web frontend will be available at `http://localhost:8081`.


## Endpoints

### Book

- `GET /api/books` - Retrieves the collection of Book resources
- `POST /api/books` - Creates a Book resource
- `GET /api/books/{id}` - Retrieves a Book resource
- `DELETE /api/books/{id}` - Removes the Book resource
- `PATCH /api/books/{id}` - Updates the Book resource

### Category

- `GET /api/categories` - Retrieves the collection of Category resources
- `POST /api/categories` - Creates a Category resource
- `GET /api/categories/{id}` - Retrieves a Category resource
- `DELETE /api/categories/{id}` - Removes the Category resource
- `PATCH /api/categories/{id}` - Updates the Category resource

## Contributing

Contributions are welcome! Please open an issue or submit a pull request for any changes.

## License

This project is licensed under the MIT License. See the [LICENSE](LICENSE) file for details.

## Contact

For any contribute, suggestion, something, please contact me: [tode](mailto:c.todeschini@metarete.it).

