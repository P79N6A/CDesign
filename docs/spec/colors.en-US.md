---
category: Visual
order: 0
title: Colors
---

CDesign interprets the color system into two levels: a system-level color system and a product-level color system.

The system-level color system mainly defines the basic color palette, neutral color palette and data visualization color palette in the design of Ant Financial. The product-level color system is in the specific design process, based on the color of the system to further define the tone of the product in accordance with the requirements and function of the color.

---

## Color Model

CDesign's design team preferred to design with the HSB color model, which makes it easier for designers to have a clear psychological expectation of color when adjusting colors, as well as facilitate communication in teams.

## System-level Color System

CDesign system-level color system also comes from the "natural" design language. Designers abstract the natural scenes through the capture, combined with the technical gene of Ant Financial, forming a unique 12 colors. Further through a large number of observations, to capture the different colors of natural light under the law of change, with the art of drawing ideas, the 12 colors were derived. The definition of neutral color palette is balanced with readability, aesthetics and usability.

### Base Color Palettes

CDesign's base color palette totals 120 colors, including 12 primary colors and their derivative colors. These colors can basically include the need for color in background applications design.

`````__react
import ColorPalettes from '../../site/theme/template/Color/ColorPalettes';

ReactDOM.render(<ColorPalettes />, mountNode);
`````

CDesign's color palette also has the ability to further extend. After careful elaboration by designers and programmers, we have come up with a set of color generation tools that combine the natural variation of colors. When there is a need for further color design, designers simply define the primary colors according to certain rules and will get a complete range of derived colors automatically .

### Neutral Color Palette

`````__react
import Palette from '../../site/theme/template/Color/Palette';

ReactDOM.render(<Palette color={{ name: 'gray' }} direction="horizontal" />, mountNode);
`````

### Data Visualization  Color Palette (Coming soon)

Data visualization color palette is based on the basic color palette and neutral color palette, and based on the principle that AntV's "effective, clear, accurate and beautiful".

### Palette Generation Tool

If the above palettes do not meet your needs, you can choose a main color below, and CDesign's color generation algorithm will generate a palette for you.

`````__react
import ColorPaletteTool from '../../site/theme/template/Color/ColorPaletteTool';

ReactDOM.render(<ColorPaletteTool />, mountNode);
`````

---

## Product-level Color System

### Brand Color

<img class="preview-img no-padding" align="right" src="https://gw.alipayobjects.com/zos/rmsportal/diEtYItrQZpqsiPsadeU.png">

The brand color is one of the most intuitive visual elements used that is used to embody product characteristics and communicate ideas. When selecting colors, it is important to understand how the brand color is used in the user interface. In the basic color palette to choose the main color, we recommend choosing the color plate from the shallow depth of the sixth color as the main color. CDesign's brand color comes from blue of the base color palette, it's Hex value is 1890FF, application scenarios include: key action point, the operation status, important information highlighting, graphics and other scenes.

### Functional Color

<img class="preview-img no-padding" align="right" src="https://gw.alipayobjects.com/zos/rmsportal/rfkSGJhMIhnUYILGIlrh.png">

Functional color represents a clear message as well as status, such as success, error, failure, reminder, link and so on. Functional color selection need to comply with the user's basic understanding of color. We suggest that the functional colors should be kept as consistent as possible under a set of product systems. Do not have too much customization to interfere with the user's cognitive experience. CDesign's functional color palette is shown on the right:

### Neutral Color

<img class="preview-img no-padding" align="right" src="https://gw.alipayobjects.com/zos/rmsportal/mkaVzBvUUEcTKeUxhgpN.png">

Neutral color is mainly used in a large part of the text interface, in addition to the background, borders, dividing lines, and other scenes are also very common. Neutral color definition needs to consider the difference between dark background and light background, while incorporating the WCAG 2.0 standard. The neutral color of CDesign is based on transparency, as shown on the right:

---

## Color Application In Enterprise Product Design

In the design of background applications of Ant Financial, our attitude towards color is restrained. Color is used more based on information delivery, operational guidance and interactive feedback purposes. Above these principles that do not undermine operational efficiency and affect the clear communication of information, a rational choice of color is key. Of course, with illustrations and display page can be properly broken this idea.
