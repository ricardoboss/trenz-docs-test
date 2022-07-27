This is a simple markdown page for testing GHFM syntax features.

---

# Heading 1

## Heading 2

### Heading 3

#### Heading 4

##### Heading 5

###### Heading 6

---

**strong**

_italic_

~~striked out~~

this is `inline code`

```csharp
Console.WriteLine("This is a C# code block");
```

An inline link to [trenz.de](https://trenz.de) or as a [website reference]

[website reference]: https://trenz.de

---

Here are some HTML codeblocks:

<p align="right">I am aligned to the right</p>

<figure>
    <img alt='some logo' src='./logo.png' height='50'>
    <figcaption>This is a caption</figcaption>
</figure>

---

| Col | Col 2 | Col 3 |
|:----|:-----:|------:|
| left | center | right |
| spaaaaaaaaacer | spaaaaaaaaacer | spaaaaaaaaacer |

---

Here is a simple flow chart:

```mermaid
graph TD;
    A-->B;
    A-->C;
    B-->D;
    C-->D;
```

And here is some geojson data:

```geojson
{
  "type": "FeatureCollection",
  "features": [
    {
      "type": "Feature",
      "id": 1,
      "properties": {
        "ID": 0
      },
      "geometry": {
        "type": "Polygon",
        "coordinates": [
          [
              [-90,35],
              [-90,30],
              [-85,30],
              [-85,35],
              [-90,35]
          ]
        ]
      }
    }
  ]
}
```
