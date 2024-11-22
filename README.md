# Go Bookings
This is a bookings web application using Go.

## Dependencies
- [chi router](https://github.com/go-chi/chi) - router management
- [SCS](https://github.com/alexedwards/scs/v2) - session management
- [nosurf](https://github.com/jusintas/nosurf) - CSRF management


## Tips
To compile multiple files in Go:
```bash
go run .
```

After refactoring:
```bash
go run cmd/web/*.go
```

Last structure:
```bash
go run ./cmd/web
```



