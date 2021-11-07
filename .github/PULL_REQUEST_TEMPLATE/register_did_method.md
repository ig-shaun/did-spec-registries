## Register a DID Method

### Required Registration Criteria

Please confirm:

- [ ] The DID Method specification defines the identifer syntax.
- [ ] The DID Method specification defines the supported DID Operations.
- [ ] The DID Method specification contains a Privacy and Security Considerations.

### Optional Registration Criteria

Consider ensuring:

- [ ] The registration entry contains contact information.
- [ ] The registration entry contains registry information.

### Registration Process

In order to register a New DID Method, you must add a json file to [./methods](./methods).

Here is an example registration entry:

```jsonc
{
  // These fields are required
  "name": "example",
  "status": "registered",
  "specification": "https://w3c-ccg.github.io/did-spec/",
  // These fields are optional
  "contactName": "W3C Credentials Community Group",
  "contactEmail": "",
  "contactWebsite": "",
  "verifiableDataRegistry": "DID Specification"
}
```

Please ensure your pull request and entry pass the required validation rules.

### Registration Review Process

Your pull request will be reviewed by the registry editors.

Changes regarding the required criteria may be requested.

If there are no objections or changes requested, 
your method will be registered after a minimum of 7 days.