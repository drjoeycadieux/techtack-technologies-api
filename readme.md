<h1 style="align: center;">
  <img src="/assets/css/logo_main.jpg" alt="logo" width="200"/>
</h1>

# Techtack-Technologies - Open Data
1. First of all You visit techtack-technologies.com
2. You go to about-us in dropdown
3. and you click open-data
4. you scroll-down until you see See our system real-time data!


### Once you here `our system real-time data!`
- You will see a button `Access api feed`
- It will open a new page with json code
- you choose one of those link
- done!

## How to code in json

```JSON
 {
    "links": {
        "self": "http://example.com/articles",
        "next": "http://example.com/articles?page[offset]=2",
        "last": "http://example.com/articles?page[offset]=10"
    },
    "data": [
        {
            "type": "articles",
            "id": "1",
            "attributes": {
                "title": "JSON:API paints my bikeshed!"
            },
            "relationships": {
                "author": {
                    "links": {
                        "self": "http://example.com/articles/1/relationships/author",
                        "related": "http://example.com/articles/1/author"
                    },
                    "data": {
                        "type": "people",
                        "id": "9"
                    }
                },
                "comments": {
                    "links": {
                        "self": "http://example.com/articles/1/relationships/comments",
                        "related": "http://example.com/articles/1/comments"
                    },
                    "data": [
                        {
                            "type": "comments",
                            "id": "5"
                        },
```

### Example of the html file


```HTML
 <div id="apiDataContainer">
<!-- Fetched data will be displayed here -->
</div>
```
