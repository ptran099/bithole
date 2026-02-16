# bithole

## API Specification

### JSON Objects
    PublicUser {
        username
    }

    User {
        username,
        email
    }

### Document what API endpoints return
    get /api/v1/user/<username> -> PublicUser
    
    // If signed in, return your own user
    get /api/v1/user -> User
