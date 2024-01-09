## Markdown Editor
<img src="https://github.com/Qiugu-He/20-React-App/blob/master/02-Markdown_Editor/Markdown_Editor.png" alt="alt text" width="100%" height="100%">
This small app is primarily practicing react hook - useState() by built a Markdown Editor

<b>useState()</b>: used for creating state varibale 
     ,and if state varible any time is changed, react will go ahead and re-render this component

### Re-destructuring state:
```java
const [markdown, setMarkdown] = useState('# Markdown Editor');
```
### handleChange(): 
every time type on this onChange will set the text value in this textarea
```java
  function handleChange(e){
    setMarkdown(e.target.value);
  }
```

### React Markdown package:
```
import ReactMarkdown from 'react-markdown';

```

## How to Run :
- npm install<br>
- npm run
- npm build (For production)