# flipmart-store
FlipMart Online Shopping Website
id: 1,
    name: "Smartphone (Demo Model)",
    price: 12999,
    image: "images/phone.png"
    id: 3,
    name: "Customized Name Coffee Mug",
    price: 399,                         
    image: "images/custom-mug.jpg",  
    isCustomizable: true  product.isCustomizable) {
    productCard.innerHTML += `
        <div class="custom-input-section" style="margin: 10px 0;">
            <label style="font-size: 12px; color: #555;">Mug</label>
            <input type="text" id="custom-text-${product.id}" placeholder= style="width: 100%; padding: 5px; margin-top: 5px; border: 1px solid #ccc; border-radius: 4px;">
        </div>
    `;
}              
