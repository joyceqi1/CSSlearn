* flex布局

  * 设置display属性为flex，container属性

    | 属性名称        | 可选值                                                       | 含义                  |
    | --------------- | ------------------------------------------------------------ | --------------------- |
    | flex-warp       | nowarp,warp,warp-reverse                                     | 是否换行              |
    | flex-direction  | row,row-reverse,colunm,colunm-reverse                        | 主轴方向              |
    | justify-content | flex-start,flex-end,center,space-between,space-around,space-evenly | 主轴对齐              |
    | align-items     | stretch,flex-start,flex-end,center,baseline                  | 交叉轴对齐方式        |
    | flex-flow       | \<flex-warp>\<flex-direction>                                | warp和direction的合并 |
    | align-conteng   | stretch \| flex-start \| flex-end \| center \| space-between \| space-around \| space-evenly | 多行项目对齐方式      |
    |                 |                                                              |                       |
    |                 |                                                              |                       |
    |                 |                                                              |                       |

    

  * item属性

    | 属性名称    | 可选值                                                       | 含义                       |
    | ----------- | ------------------------------------------------------------ | -------------------------- |
    | algin-self  | auto \| flex-start \| flex-end \| center \| baseline \| stretch | 项目本身在交叉轴的对齐方式 |
    | flex-grow   | number                                                       | 项目在主轴放大比例         |
    | flex-shrink | number                                                       | 项目在主轴缩小比例         |
    | flex-basis  | length\|auto                                                 | 设置项目尺寸               |
    | flex        | \<flex-grow> \<flex-shrink> \<flex-basis>                    |                            |
    | order       | 0，正，负                                                    | 项目在主轴上的排列顺序     |

    

    