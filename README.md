# CSS_FLEX
Pages to Design

Create five different pages that utilize CSS Flexbox to arrange elements.

Page 1: Product Layout

Display products in a grid with images, names, and prices.

Flexbox Features Used:

display: flex;

flex-wrap: wrap;

justify-content: space-between;

<!-- products.html -->
<div class="product-layout">
  <div class="product-card">
    <img src="product1.jpg" alt="Product 1">
    <h3>Product Name</h3>
    <p>$10.00</p>
  </div>
  <div class="product-card">
    <img src="product2.jpg" alt="Product 2">
    <h3>Product Name</h3>
    <p>$20.00</p>
  </div>
</div>


/* styles.css */
.product-layout {
  display: flex;
  flex-wrap: wrap;
  gap: 20px;
}
.product-card {
  flex: 1 1 calc(33.333% - 20px);
  text-align: center;
}


Employee Cards

A horizontal row of employee cards with names, positions, and photos.

Flexbox Features Used:

align-items: center;

gap.

Student Profiles

Profiles displayed in rows and columns with student photos and details.

Flexbox Features Used:

flex-direction: column;

align-items.

Photo Gallery

Create a responsive gallery layout.

Flexbox Features Used:

flex-grow to adjust image sizes dynamically.

Contact Form

Layout with evenly spaced fields and a submit button.

Flexbox Features Used:

flex-direction: column.

products.html: Product layout using Flexbox for grid design.
employees.html: Employee cards in a row layout.
students.html: Student profiles displayed flexibly in columns.
gallery.html: Responsive photo gallery.
contact.html: Simple form layout with Flexbox.
