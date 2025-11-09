# 🥜 Sample Products to Add

Use these product templates to expand your NutsSphere catalog!

## How to Add Products

1. Open `script.js`
2. Find the `productsData` array (around line 56)
3. Copy a product template below
4. Paste it into the array
5. Modify the details
6. Add the product image to the `images/` folder

---

## Nuts Category

### 1. Premium Cashews
```javascript
{
    id: 'premium-cashews',
    name: 'Premium Cashews',
    category: 'nuts',
    description: 'Whole cashew nuts, rich in healthy fats and minerals. Perfect for snacking or cooking.',
    image: 'images/cashews.jpg',
    price: 549,
    originalPrice: 649,
    discount: 15,
    variants: [
        { size: '250g', price: 549 },
        { size: '500g', price: 1049 },
        { size: '1kg', price: 1999 }
    ],
    features: ['Protein Rich', 'Heart Healthy', 'Vegan'],
    badges: ['Premium Quality', 'Whole'],
    inStock: true
},
```

### 2. Roasted Almonds
```javascript
{
    id: 'roasted-almonds',
    name: 'Roasted Almonds',
    category: 'nuts',
    description: 'Lightly roasted almonds for enhanced flavor. Rich in Vitamin E and antioxidants.',
    image: 'images/roasted-almonds.jpg',
    price: 799,
    originalPrice: 899,
    discount: 11,
    variants: [
        { size: '250g', price: 799 },
        { size: '500g', price: 1499 },
        { size: '1kg', price: 2899 }
    ],
    features: ['Vitamin E', 'Antioxidants', 'Roasted'],
    badges: ['Bestseller', 'Roasted'],
    inStock: true
},
```

### 3. Brazil Nuts
```javascript
{
    id: 'brazil-nuts',
    name: 'Brazil Nuts',
    category: 'nuts',
    description: 'Premium Brazil nuts, an excellent source of selenium. Supports immune health.',
    image: 'images/brazil-nuts.jpg',
    price: 899,
    originalPrice: 1099,
    discount: 18,
    variants: [
        { size: '250g', price: 899 },
        { size: '500g', price: 1699 },
        { size: '1kg', price: 3199 }
    ],
    features: ['High Selenium', 'Immune Support'],
    badges: ['Premium', 'Imported'],
    inStock: true
},
```

### 4. Mixed Nuts
```javascript
{
    id: 'mixed-nuts',
    name: 'Premium Mixed Nuts',
    category: 'nuts',
    description: 'A delightful mix of almonds, cashews, walnuts, and pistachios. Perfect for any occasion.',
    image: 'images/mixed-nuts.jpg',
    price: 699,
    originalPrice: 799,
    discount: 13,
    variants: [
        { size: '250g', price: 699 },
        { size: '500g', price: 1299 },
        { size: '1kg', price: 2499 }
    ],
    features: ['Variety Pack', 'All Natural', 'No Preservatives'],
    badges: ['Bestseller', 'Premium Mix'],
    inStock: true
},
```

### 5. Hazelnuts
```javascript
{
    id: 'hazelnuts',
    name: 'Whole Hazelnuts',
    category: 'nuts',
    description: 'Premium quality hazelnuts, rich in fiber and antioxidants. Great for baking and snacking.',
    image: 'images/hazelnuts.jpg',
    price: 849,
    originalPrice: 999,
    discount: 15,
    variants: [
        { size: '250g', price: 849 },
        { size: '500g', price: 1599 },
        { size: '1kg', price: 2999 }
    ],
    features: ['High Fiber', 'Antioxidants'],
    badges: ['Premium', 'Whole'],
    inStock: true
},
```

---

## Seeds Category

### 1. Chia Seeds
```javascript
{
    id: 'chia-seeds',
    name: 'Organic Chia Seeds',
    category: 'seeds',
    description: 'Premium organic chia seeds, packed with omega-3 and fiber. Superfood for a healthy lifestyle.',
    image: 'images/chia-seeds.jpg',
    price: 299,
    originalPrice: 399,
    discount: 25,
    variants: [
        { size: '250g', price: 299 },
        { size: '500g', price: 549 },
        { size: '1kg', price: 999 }
    ],
    features: ['Omega-3', 'High Fiber', 'Gluten Free'],
    badges: ['Organic', 'Superfood'],
    inStock: true
},
```

### 2. Flax Seeds
```javascript
{
    id: 'flax-seeds',
    name: 'Golden Flax Seeds',
    category: 'seeds',
    description: 'Premium golden flax seeds, rich in omega-3 and lignans. Supports heart health.',
    image: 'images/flax-seeds.jpg',
    price: 249,
    originalPrice: 329,
    discount: 24,
    variants: [
        { size: '250g', price: 249 },
        { size: '500g', price: 449 },
        { size: '1kg', price: 849 }
    ],
    features: ['Omega-3', 'Heart Healthy', 'High Protein'],
    badges: ['Organic', 'Golden'],
    inStock: true
},
```

### 3. Pumpkin Seeds
```javascript
{
    id: 'pumpkin-seeds',
    name: 'Roasted Pumpkin Seeds',
    category: 'seeds',
    description: 'Lightly salted roasted pumpkin seeds. Rich in zinc and magnesium.',
    image: 'images/pumpkin-seeds.jpg',
    price: 349,
    originalPrice: 449,
    discount: 22,
    variants: [
        { size: '250g', price: 349 },
        { size: '500g', price: 649 },
        { size: '1kg', price: 1199 }
    ],
    features: ['High Zinc', 'Magnesium', 'Roasted'],
    badges: ['Roasted', 'Salted'],
    inStock: true
},
```

### 4. Sunflower Seeds
```javascript
{
    id: 'sunflower-seeds',
    name: 'Sunflower Seeds',
    category: 'seeds',
    description: 'Premium sunflower seeds, rich in Vitamin E and selenium. Perfect healthy snack.',
    image: 'images/sunflower-seeds.jpg',
    price: 199,
    originalPrice: 259,
    discount: 23,
    variants: [
        { size: '250g', price: 199 },
        { size: '500g', price: 379 },
        { size: '1kg', price: 699 }
    ],
    features: ['Vitamin E', 'Selenium', 'Protein'],
    badges: ['Organic', 'Raw'],
    inStock: true
},
```

### 5. Quinoa Seeds
```javascript
{
    id: 'quinoa-seeds',
    name: 'Organic Quinoa',
    category: 'seeds',
    description: 'Premium white quinoa, a complete protein source. Gluten-free superfood.',
    image: 'images/quinoa.jpg',
    price: 399,
    originalPrice: 499,
    discount: 20,
    variants: [
        { size: '250g', price: 399 },
        { size: '500g', price: 749 },
        { size: '1kg', price: 1399 }
    ],
    features: ['Complete Protein', 'Gluten Free', 'High Fiber'],
    badges: ['Organic', 'Superfood'],
    inStock: true
},
```

---

## Dried Fruits Category

### 1. Dried Apricots
```javascript
{
    id: 'dried-apricots',
    name: 'Turkish Apricots',
    category: 'dried-fruits',
    description: 'Premium Turkish dried apricots, naturally sweet and rich in fiber. No added sugar.',
    image: 'images/apricots.jpg',
    price: 449,
    originalPrice: 549,
    discount: 18,
    variants: [
        { size: '250g', price: 449 },
        { size: '500g', price: 849 },
        { size: '1kg', price: 1599 }
    ],
    features: ['Natural Sugar', 'High Fiber', 'Iron Rich'],
    badges: ['Turkish', 'Premium'],
    inStock: true
},
```

### 2. Dates
```javascript
{
    id: 'medjool-dates',
    name: 'Medjool Dates',
    category: 'dried-fruits',
    description: 'Premium Medjool dates, naturally sweet and energy-rich. Perfect for snacking.',
    image: 'images/dates.jpg',
    price: 599,
    originalPrice: 699,
    discount: 14,
    variants: [
        { size: '250g', price: 599 },
        { size: '500g', price: 1099 },
        { size: '1kg', price: 2099 }
    ],
    features: ['Natural Energy', 'High Potassium', 'No Added Sugar'],
    badges: ['Medjool', 'Premium'],
    inStock: true
},
```

### 3. Dried Figs
```javascript
{
    id: 'dried-figs',
    name: 'Turkish Figs',
    category: 'dried-fruits',
    description: 'Premium sun-dried Turkish figs. Rich in calcium and natural sweetness.',
    image: 'images/figs.jpg',
    price: 549,
    originalPrice: 649,
    discount: 15,
    variants: [
        { size: '250g', price: 549 },
        { size: '500g', price: 1049 },
        { size: '1kg', price: 1999 }
    ],
    features: ['Calcium Rich', 'Natural Sweet', 'High Fiber'],
    badges: ['Turkish', 'Sun-Dried'],
    inStock: true
},
```

### 4. Dried Cranberries
```javascript
{
    id: 'dried-cranberries',
    name: 'Dried Cranberries',
    category: 'dried-fruits',
    description: 'Premium dried cranberries, rich in antioxidants. Lightly sweetened.',
    image: 'images/cranberries.jpg',
    price: 399,
    originalPrice: 499,
    discount: 20,
    variants: [
        { size: '250g', price: 399 },
        { size: '500g', price: 749 },
        { size: '1kg', price: 1399 }
    ],
    features: ['Antioxidants', 'Vitamin C', 'Urinary Health'],
    badges: ['Premium', 'Sweetened'],
    inStock: true
},
```

### 5. Dried Prunes
```javascript
{
    id: 'dried-prunes',
    name: 'California Prunes',
    category: 'dried-fruits',
    description: 'Premium California prunes, naturally sweet and fiber-rich. Great for digestion.',
    image: 'images/prunes.jpg',
    price: 449,
    originalPrice: 549,
    discount: 18,
    variants: [
        { size: '250g', price: 449 },
        { size: '500g', price: 849 },
        { size: '1kg', price: 1599 }
    ],
    features: ['Digestive Health', 'High Fiber', 'Bone Health'],
    badges: ['California', 'Pitted'],
    inStock: true
},
```

---

## Superfoods Category

### 1. Goji Berries
```javascript
{
    id: 'goji-berries',
    name: 'Organic Goji Berries',
    category: 'superfoods',
    description: 'Premium Himalayan goji berries, packed with antioxidants and vitamins.',
    image: 'images/goji-berries.jpg',
    price: 699,
    originalPrice: 849,
    discount: 18,
    variants: [
        { size: '250g', price: 699 },
        { size: '500g', price: 1299 },
        { size: '1kg', price: 2499 }
    ],
    features: ['Antioxidants', 'Immune Boost', 'Vitamin C'],
    badges: ['Organic', 'Superfood'],
    inStock: true
},
```

### 2. Spirulina Powder
```javascript
{
    id: 'spirulina-powder',
    name: 'Organic Spirulina Powder',
    category: 'superfoods',
    description: 'Premium spirulina powder, rich in protein and vitamins. Detox superfood.',
    image: 'images/spirulina.jpg',
    price: 799,
    originalPrice: 999,
    discount: 20,
    variants: [
        { size: '100g', price: 799 },
        { size: '250g', price: 1799 },
        { size: '500g', price: 3299 }
    ],
    features: ['High Protein', 'Detox', 'B Vitamins'],
    badges: ['Organic', 'Superfood'],
    inStock: true
},
```

### 3. Moringa Powder
```javascript
{
    id: 'moringa-powder',
    name: 'Organic Moringa Powder',
    category: 'superfoods',
    description: 'Premium moringa leaf powder, nutrient-dense superfood. Supports overall wellness.',
    image: 'images/moringa.jpg',
    price: 499,
    originalPrice: 649,
    discount: 23,
    variants: [
        { size: '100g', price: 499 },
        { size: '250g', price: 1099 },
        { size: '500g', price: 1999 }
    ],
    features: ['Nutrient Dense', 'Anti-inflammatory', 'Immune Support'],
    badges: ['Organic', 'Superfood'],
    inStock: true
},
```

### 4. Açaí Berry Powder
```javascript
{
    id: 'acai-powder',
    name: 'Açaí Berry Powder',
    category: 'superfoods',
    description: 'Premium freeze-dried açaí powder. Rich in antioxidants and healthy fats.',
    image: 'images/acai.jpg',
    price: 899,
    originalPrice: 1199,
    discount: 25,
    variants: [
        { size: '100g', price: 899 },
        { size: '250g', price: 1999 },
        { size: '500g', price: 3699 }
    ],
    features: ['Antioxidants', 'Omega Fats', 'Energy Boost'],
    badges: ['Freeze-Dried', 'Superfood'],
    inStock: true
},
```

### 5. Maca Powder
```javascript
{
    id: 'maca-powder',
    name: 'Organic Maca Root Powder',
    category: 'superfoods',
    description: 'Premium Peruvian maca powder. Supports energy and hormonal balance.',
    image: 'images/maca.jpg',
    price: 649,
    originalPrice: 799,
    discount: 19,
    variants: [
        { size: '100g', price: 649 },
        { size: '250g', price: 1399 },
        { size: '500g', price: 2599 }
    ],
    features: ['Energy Boost', 'Hormonal Balance', 'Adaptogen'],
    badges: ['Organic', 'Peruvian'],
    inStock: true
},
```

---

## Gift Packs & Combos

### 1. Health Pack
```javascript
{
    id: 'health-pack',
    name: 'Complete Health Pack',
    category: 'superfoods',
    description: 'A perfect combination of nuts, seeds, and dried fruits for complete nutrition.',
    image: 'images/health-pack.jpg',
    price: 1499,
    originalPrice: 1999,
    discount: 25,
    variants: [
        { size: 'Standard', price: 1499 },
        { size: 'Premium', price: 2499 }
    ],
    features: ['Complete Nutrition', 'Gift Pack', 'Variety'],
    badges: ['Bestseller', 'Gift Pack'],
    inStock: true
},
```

### 2. Trail Mix
```javascript
{
    id: 'trail-mix',
    name: 'Energy Trail Mix',
    category: 'nuts',
    description: 'A perfect blend of nuts, seeds, and dried fruits. Ideal for hiking and sports.',
    image: 'images/trail-mix.jpg',
    price: 549,
    originalPrice: 699,
    discount: 21,
    variants: [
        { size: '250g', price: 549 },
        { size: '500g', price: 1049 },
        { size: '1kg', price: 1999 }
    ],
    features: ['High Energy', 'Protein Rich', 'No Preservatives'],
    badges: ['Bestseller', 'Trail Mix'],
    inStock: true
},
```

---

## Tips for Product Images

### Image Requirements:
- **Format**: JPG or PNG
- **Size**: 800x800px (square)
- **Quality**: High resolution but optimized
- **Background**: White or transparent
- **File Size**: Under 200KB

### Where to Get Images:
1. **Your Own Photos**: Best option for authenticity
2. **Stock Photos**: Pexels, Unsplash, Pixabay
3. **Product Suppliers**: Get from your vendors
4. **Professional Photography**: Hire a photographer

### Image Naming:
- Use lowercase
- Use hyphens for spaces
- Be descriptive
- Example: `organic-chia-seeds.jpg`

---

## Product Categories Explained

- **nuts**: All types of nuts (almonds, cashews, walnuts, etc.)
- **seeds**: All types of seeds (chia, flax, pumpkin, etc.)
- **dried-fruits**: All dried fruits (raisins, dates, apricots, etc.)
- **superfoods**: Superfood powders and special items

---

## Next Steps

1. Choose products you want to sell
2. Take or source high-quality images
3. Add images to `images/` folder
4. Copy product template
5. Update product details
6. Add to `productsData` array in `script.js`
7. Test the product display
8. Repeat for all products

---

**Happy Selling! 🎉**