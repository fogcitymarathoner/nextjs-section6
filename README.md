
# lesson take-aways

## JSON shortcuts
```aiignore
    const title = formData.get('title');
    const image = formData.get('image');
    const content = formData.get('content');

    storePost({
      imageUrl: '',
      title,  // <====
      content,
      userId: 1
    })
```