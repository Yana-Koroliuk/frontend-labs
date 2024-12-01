# frontend-labs

## Lab 1 : Description
In folder lab-1 showcases implementations of various web layout techniques, including Table, Float, CSS Grid, and Flexbox. It aims to demonstrate the advantages, limitations, and appropriate use cases of each approach in web development. All layouts are responsive and designed to adapt seamlessly to different screen sizes.
This repository in folder lab-1 includes several HTML and CSS implementations of web layouts designed to:

- illustrate the application of different CSS layout techniques.
- highlight the adaptability of layouts for various screen sizes.
- provide insights into the strengths and limitations of each layout type.

## Technologies used

- **HTML5**: Markup language for structuring web content.
- **CSS3**: Styling language used to implement layout techniques (Table, Float, Grid, Flexbox).

## Layouts description

### 1. Table layout

#### **Strengths**
- Simple to implement for static designs.

#### **Limitations**
- Poor adaptability for responsive designs.
- Outdated for modern web development due to lack of semantic and flexible properties.

### 2. Float layout

#### **Strengths**
- Effective for small-scale tasks like text wrapping around images.

#### **Limitations**
- Requires additional clearing and manual adjustments for responsiveness.
- Less intuitive compared to modern layout methods like Flexbox and Grid.

### 3. CSS Grid layout

#### **Strengths**
- Ideal for complex, two-dimensional layouts with rows and columns.
- Highly responsive, with fewer nested elements.

#### **Limitations**
- May be overly complex for simpler, one-dimensional layouts.

### 4. Flexbox layout

#### **Strengths**
- Excellent for single-axis alignment and dynamic spacing.
- Simplifies adaptive design for different screen sizes.

#### **Limitations**
- Less suitable for complex two-dimensional layouts.


## Features

- Responsive design implemented for all layouts.
- Clean and semantic HTML5 structure.
- Adaptive layouts for mobile, tablet, and desktop screens.
- Demonstration of both modern and older CSS layout techniques.

## How to Run

1. Clone this repository:
   ```bash
   git clone https://github.com/Yana-Koroliuk/frontend-labs.git
   ```
2. Open the desired HTML file in your browser:
   ```bash
   open index.html
   ```

## Conclusions

1. **Table Layout**:
    - Best suited for simple, static designs.
    - Lacks adaptability and modern semantic advantages.

2. **Float Layout**:
    - Useful for small-scale tasks but outdated for full-page layouts.
    - Requires significant adjustments for responsive designs.

3. **CSS Grid Layout**:
    - Ideal for complex, two-dimensional layouts requiring precise row and column placement.
    - Reduces the need for additional HTML elements.

4. **Flexbox Layout**:
    - Perfect for dynamic, one-dimensional layouts requiring alignment and responsiveness.
    - Offers unmatched flexibility for adaptive designs.

### General recommendation

In modern web development, **CSS Grid** and **Flexbox** are the preferred choices due to their simplicity, flexibility, and adaptability to different screen sizes.

## Lab 2: Description

For all pages in lab-2, style compilation was set up using two different methods: Stylus and SASS.

## Setup for Style Compilation
### Stylus/SASS

1. Clone this repository:
   ```bash
   git clone https://github.com/Yana-Koroliuk/frontend-labs.git
   ```
2. Install Stylus/SASS via npm:
   ```bash
   npm install stylus -g
   ```
   ```bash
   npm install sass -g
   ```
3. Compile Stylus/SASS to CSS with the following command:
   ```bash
   stylus lab-2/template-1/stylus.styl -o lab-2/template-1/styles.css
   ```
   ```bash
   sass lab-2/template-1/sass.scss lab-2/template-1/styles.css
   ```
   
## Summary of CSS Preprocessors

### Stylus

#### Advantages
- Compact and minimalistic syntax.
- Offers flexibility through mixins, variables, and simple conditions.
- Fast development for projects with straightforward structures.

#### Disadvantages
- Minimalistic nature can complicate collaboration and maintenance for larger teams.
- Limited scalability for large projects due to less emphasis on structured organization.

### SASS

#### Advantages
- Supports nested styles that align well with HTML structure.
- Enables robust organization through strict syntax.
- Provides mixins with parameters, conditional constructs, and other advanced features.
- Better suited for scaling and integrating into large projects.

#### Disadvantages
- Requires more attention to syntax details compared to Stylus.
- Overly deep nesting may reduce performance and readability.

### General recommendation
Stylus is ideal for small projects or rapid prototyping due to its concise syntax. However, for large-scale or long-term projects, SASS is a more powerful and organized tool, though it demands more effort in the initial setup.