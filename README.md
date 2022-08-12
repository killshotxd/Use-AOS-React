import React, { useEffect } from "react";
import AOS from "aos";
import "aos/dist/aos.css";

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
