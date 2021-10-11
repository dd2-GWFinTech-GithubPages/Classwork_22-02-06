# Classwork_22-02-06

**Welcome to the CryptoRight Website!**

## Demo Website

Navigate to the following link for the demo!

[CryptoRight Website](frontend/index.html)

## Technical Description

Core data is stored inside the `copyrights` mapping structure.

```python
    mapping(uint => Work) public copyrights;
```

Events are defined in the next section.

```python
    event Copyright(uint copyright_id, address owner, string reference_uri);

    event OpenSource(uint copyright_id, string reference_uri);

    event Transfer(uint copyright_id, address new_owner);
```

