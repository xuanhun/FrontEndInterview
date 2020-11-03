
## 容器宽度计算

const root=container
var stl = document.defaultView.getComputedStyle(root);


const width = (root["clientWidth"]|| stl["width"] || root.style["width"] - stl["paddingLeft"] - stl["paddingRight"]) | 0;

const height = (root["clientHeight"]|| stl["height"] || root.style["height"] - stl["paddingTop"] - stl["paddingBottom"]) | 0;



