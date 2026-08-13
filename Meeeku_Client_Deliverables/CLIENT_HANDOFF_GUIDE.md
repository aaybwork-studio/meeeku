# 🎀 Meeeku Kidswear — Client Handoff & Store Guide

Welcome to the official client handoff package for **Meeeku Kidswear**! This package contains all high-resolution product photography, hero campaign banners, Shopify theme files, and database CSV imports ready for production deployment.

---

## 📁 Package Structure

```
Meeeku_Client_Deliverables/
├── 01_Product_Photos_HighRes/         # 9 Product Folders (Flatlay, Model, Fabric Swirl)
│   ├── 01_Sunshine_Chanderi_Lehenga/
│   ├── 02_Teal_Bloom_Dress/
│   ├── 03_Blush_Rose_Net_Lehenga/
│   ├── 04_Forest_Vrindavan_Lehenga/
│   ├── 05_Gulmohar_Splash_Coord/
│   ├── 06_Sage_Mint_Gota_Lehenga/
│   ├── 07_Rani_Pink_Phulkari_Lehenga/
│   ├── 08_Midnight_Blossom_Halter_Lehenga/
│   └── 09_Olive_Silk_OneShoulder_Lehenga/
├── 02_Homepage_Hero_Carousel_Banners/  # 16:9 Widescreen Campaign Banners
│   ├── 01_Hero_Ethnic_Wear_16x9.jpg
│   ├── 02_Hero_Festive_Dresses_16x9.jpg
│   └── 03_Hero_CoOrd_Sets_16x9.jpg
├── 03_Shopify_Product_CSV_Import/     # Ready-to-import Shopify Product CSV
│   └── Meeeku_Shopify_Products_Import.csv
├── 04_Shopify_Theme_Zip_Package/       # Standard Shopify Theme Zip
│   └── Meeeku_Shopify_Theme_v1.0.zip
└── CLIENT_HANDOFF_GUIDE.md             # Handoff Documentation & Setup Guide
```

---

## 👗 Complete Product Catalog & Pricing

| # | Product Name | Category | Price (INR) | Compare Price (MRP) | Key Highlights |
|---|---|---|---|---|---|
| 1 | **Sunshine Chanderi Lehenga** | Royal Ethnic | ₹3,199.00 | ₹3,899.00 | Chanderi Cotton, 100% Muslin Cotton Lining |
| 2 | **Teal Bloom Dress** | Tulle & Sequins | ₹2,999.00 | ₹3,699.00 | Hand-embroidered Gold Sequins, Tulle Net Skirt |
| 3 | **Blush Rose Net Lehenga** | Royal Net & Zari | ₹3,299.00 | ₹3,999.00 | Scalloped Gold Lace Trim, Jacquard Fabric |
| 4 | **Forest Vrindavan Lehenga** | Organic Cotton | ₹3,199.00 | ₹3,899.00 | Emerald Green, White Embroidery, Silver Gota Patti |
| 5 | **Gulmohar Splash Co-ord** | Festive Co-ord | ₹2,899.00 | ₹3,599.00 | Vibrant Abstract Floral Rayon Print |
| 6 | **Sage Mint Gota Lehenga** | Gota Patti Zari | ₹3,199.00 | ₹3,899.00 | Sage Mint Linen Cotton, Red Flower Embroidery |
| 7 | **Rani Pink Phulkari Lehenga** | Phulkari Threadwork | ₹2,799.00 | ₹3,499.00 | Rani Magenta, Multi-color Threadwork |
| 8 | **Midnight Blossom Halter Lehenga** | Royal Halter Neck | ₹2,799.00 | ₹3,499.00 | Midnight Black, Crimson Floral Blockprint |
| 9 | **Olive Silk One-Shoulder Lehenga** | Zardozi Silk | ₹3,299.00 | ₹3,999.00 | Olive Chartreuse Satin Silk, Silver Zardozi Vines |


---

## ⚡ Deployment Instructions for Shopify

### 1. Import Theme Zip
1. Log into **Shopify Admin** (`yourstore.myshopify.com/admin`).
2. Go to **Online Store > Themes**.
3. Under *Theme Library*, click **Add theme > Upload zip file**.
4. Select `04_Shopify_Theme_Zip_Package/Meeeku_Shopify_Theme_v1.0.zip`.
5. Click **Publish** to make it live.

### 2. Import Products via CSV
1. In Shopify Admin, go to **Products**.
2. Click **Import** at the top right.
3. Choose `03_Shopify_Product_CSV_Import/Meeeku_Shopify_Products_Import.csv`.
4. Check **Overwrite any current products that have the same handle**.
5. Click **Import products**.

### 3. Setup Discount Code WELCOME15
1. Go to **Discounts > Create discount**.
2. Select **Amount off products** (or Amount off order).
3. Set discount code: `WELCOME15`.
4. Set discount percentage: `15%`.
5. Set minimum purchase requirement to None (or first orders).
6. Click **Save**.

---

## 🎨 Asset Naming Convention

Every product folder inside `01_Product_Photos_HighRes/` follows a standardized naming standard:
- `01_Flatlay_Product.jpg`: Clean studio laid-out garment photo.
- `02_Model_Photo.jpg`: High-resolution child model wearing the garment.
- `03_Fabric_Swirl_CloseUp.jpg`: Macro close-up shot of the swirled fabric, embroidery & trim.

---
*Created by Antigravity AI for Meeeku Kidswear.*
