```javascript
const response = await fetch(
  "https://dev.demo.sensenet.com/OData.svc/Root/Content/IT/Document_Library('Calgary')/Delete",
  {
    credentials: "include",
    method: "POST",
    body: JSON.stringify({
      permanent: true
    })
  }
);
```
