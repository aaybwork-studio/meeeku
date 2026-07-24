# Meeeku Shopify Theme Roadmap

## Phase 1: Repository Foundation & Base Theme Import
- Download & set up official Shopify Dawn baseline theme structure into workspace
- Initialize Git repository and link to `https://github.com/aaybwork-studio/meeeku`
- Commit baseline theme to main branch

## Phase 2: Brand Styling & Theme Settings Customization
- Update `config/settings_data.json` & `config/settings_schema.json` with Meeeku color tokens (Soft Pastel Pink, Lavender, Warm Cream)
- Add custom font imports, rounded buttons, card shadows, and soft scalloped borders in `assets/base.css`
- Configure Header & Footer with Meeeku logo (`logo.png`) and custom navigation links

## Phase 3: Custom Liquid Sections & Components Development
- Build `sections/meeeku-hero-slider.liquid` for Indian Ethnic & Nightsuits featured collections
- Build `sections/meeeku-boys-coming-soon.liquid` with email notify drawer/modal
- Build `snippets/meeeku-size-guide.liquid` for 2-5Y kids ethnic & nightwear fit charts
- Enhance `snippets/buy-buttons.liquid` & cart drawer with Sticky Quick-Add drawer functionality

## Phase 4: Product Data & High-Res Placeholder Media Generation
- Use Nanobana image generator to create high quality placeholder images for Indian Ethnic (3 items) & Nightsuits (3 items)
- Populate sample JSON product data & featured collection templates

## Phase 5: Verification, Git Push & Shopify Sync Readiness
- Run Theme linting / Liquid checks
- Push clean code to GitHub repo `https://github.com/aaybwork-studio/meeeku`
- Provide step-by-step instructions for importing the GitHub repo directly into Shopify Admin
