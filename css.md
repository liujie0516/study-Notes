perspective和transform: translate3d结合怎么使用？

//立体位移效果：
container {
  perspective: 800px;
  perspective-origin: center center; /* 设置视角原点 */
}

.box {
  transform: translate3d(100px, 100px, -200px);
}
