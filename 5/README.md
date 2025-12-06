

# ვიდეოს, ფოტოს და აუდიო ფაილების გადმოსაწერი ლინკები:
# - [pixabay.com](https://pixabay.com/videos/)

# HTML `<audio>` ტეგი

| ატრიბუტი | აღწერა | მნიშვნელობა |
|-----------|-------------|----------------|
| `source ტეგი `(src) | აუდიოს მისამართი | მისამართი |
| autoplay | აუდიოს რთავს ავტომატურად | boolean |
| controls | აჩვენებს აუდიოზე სხვადასხვა საკონტროლო საშუალებას | boolean |
| loop | ამეორებს აუდიოს დასრულების შემდეგ | boolean |
| muted | ნაგულისხმევად აუდიოს უხმოდ ჩატვირთვა | boolean |
| preload | აუდიოს წინასწარი ჩატვირთვა | none, metadata, auto |

# HTML სიის ტეგები

| ტეგები | აღწერა | ატრიბუტები |
|-----------|-------------|----------------|
| ul | დაუნომრავი სია | type |
| ol | სორტირებული სია | type (1, A, a, I, i), start (ციფრი) |
| li | სიის ელემენტი | - | 
| | | - |
| dl | განმარტებითი სია | - |
| dt | განმარტების ტერმინი | - |
| dd | განმარტების აღწერა | - |

# HTML `<table>` ტეგი 

| ტეგები | აღწერა | ატრიბუტები |
|-----------|-------------|----------------|
| table | ცხრილი | `border (ციფრი), cellpadding დაშორება (ციფრი), cellspacing (ციფრი), width (ციფრი ან პროცენტი), height (ციფრი ან პროცენტი)`, align (left, center, right) |
| tr | ცხრილის სვეტი | align (left, center, right), `bgcolor (ფერი)` |
| th | სათაური უჯრა | `bgcolor (ფერი)`, align (left, center, right), valign (top, middle, bottom) |
| td | მონაცემთა უჯრა | `bgcolor (ფერი)`, align (left, center, right), valign (top, middle, bottom) |    
| thead | ცხრილის სათაური | - |
| tbody | ცხრილის სხეული | - |
| tfoot | ცხრილის ქვედა ნაწილი | - |
| caption | ცხრილის სათაური | align (top, bottom) |

`<table>` ტეგის მაგალითი:

```html
<table cellspacing="0" cellpadding="10">
  <tr>
    <th>Company</th>
    <th>Contact</th>
    <th>Country</th>
  </tr>
  <tr>
    <td>Alfreds Futterkiste</td>
    <td>Maria Anders</td>
    <td>Germany</td>
  </tr>
  <tr>
    <td>Centro comercial Moctezuma</td>
    <td>Francisco Chang</td>
    <td>Mexico</td>
  </tr>
</table>
```