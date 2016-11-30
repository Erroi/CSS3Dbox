1. perspective:1000px;   眼睛距屏幕的距离
2. persective-origin: 50% 50%; 视点，x y。(当为元素定义perspective-origin属性时，其 *子元素*会获得透视效果，而不是元素本身；必须与perspective一同使用；且只影响3D转换元素 )
3. transform-style: preserve-3d;默认为flat;如果要在元素上实现3D效果，就要在*父元素*上加transform-style:preserve-3d;
4. animation-fill-mode:forwards; 让子元素保持动画最后的效果，否则会恢复原样。
5. 一个物体做两次动画，则在外面再包裹一层div
6. 具体知识点请参考http://isux.tencent.com/css3/index.html 