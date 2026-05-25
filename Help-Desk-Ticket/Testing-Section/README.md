## Testing Performed

### Manual Testing

Validated:

- Home page loading
- Login page loading
- Ticket creation
- Ticket retrieval
- Ticket status updates
- Session authentication

### Integration Testing

Validated communication between:

Flask ↔ SQLite Database

### End-to-End Testing

Workflow tested:

```
Create Ticket
↓
Store Data
↓
Login As Admin
↓
Update Status
↓
Verify Database
↓
Verify User Display
```

### Automated Testing

Executed Pytest automation validating:

- Home page route
- Login route
- Tickets route
- Ticket creation route
