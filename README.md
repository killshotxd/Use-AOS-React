[![AOS - Animate on scroll library]

### Using package managers

## ⚙ Installation

Install `aos` package:

- `yarn add aos@next`
- or `npm install --save aos@next`

Import script, styles and initialize AOS:

```js
import AOS from 'aos';
import 'aos/dist/aos.css'; // You can also use <link> for styles
// ..
function App() {
useEffect(() => {
AOS.init();
AOS.refresh();
}, []);

return (
// your components
);
}

export default App;
```
