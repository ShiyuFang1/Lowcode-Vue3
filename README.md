# Lowcode Engine
The low-code framework uses JSON configuration to generate pages, which can reduce the workload of page development and greatly improve efficiency. Drag and drop users' own code components. Let non-developers create stunning content, and free up developers from pixel-pushing.

## Features

- Optional component area：users can drag and drop the used material components freely.
- Content editing area：users can layout and adjust the content by dragging and dropping.
  * **Text** editing area: Set text size, color, text box size, text content.  
  * **Drop-down box** editing area: Set radio items, add drop-down options, and bind fields.
  * **Button** editing area: Customize the button content, select the button type, and adjust the button size. 
  * **Input box** editing area: Bind texts and adjust the width of the input box.  
  * **Range selector**: Set start range and end range.  
- Property setting area：users can set property settings in the selected area.

## Demo

##### Generate Component

![WeChat_20220922231412](D:\LowCode-main\WeChat_20220922231412.gif)

##### Edit page 

![](D:\LowCode-main\WeChat_20220922231438.gif)

##### Export JSON file

![WeChat_20220922231456](D:\LowCode-main\WeChat_20220922231456.gif)



## Testing Result

##### Function Test

The drag and drag component (text, buttons, input box, drop -down box, digital range input box) can customize the page you need, you can directly modify the style of the component through the right menu bar. User can redefine all operations. export and import the JSON files that can be introduced to the page, which can preview the effect of the page.

Test case of component:
modify the component style and adjust the component size

![微信截图_20220922230315](D:\LowCode-main\微信截图_20220922230315.png)

Import/export JSON file

![微信截图_20220922230408](D:\LowCode-main\微信截图_20220922230408.png)

##### Performance Test

Loading time: 1.50s

![image](D:\LowCode-main\image.png)

##### LightHouse

![0aa7a19a-9a96-4510-8a11-6bedb3aa576e](D:\LowCode-main\0aa7a19a-9a96-4510-8a11-6bedb3aa576e.png)



![test2](D:\LowCode-main\test2.png)

## Quick Start

##### Install 

```sh
npm install
```

##### run

```sh
npm run serve
```

##### build

```
npm run build
```





