# ShinePro Shopify Theme

ShinePro is a high-performance, responsive Shopify theme optimized for visual excellence, micro-interactions, and premium conversion features.

## Key Features

- **Jolly Good Testimonials Slider**: A fully responsive customer testimonial carousel with:
  - Responsive layouts (3 cards on desktop, 2 on tablet, and 1 swipeable card on mobile).
  - Smooth right-to-left autoplay on desktop and tablet screens (paused automatically on hover).
  - Interactive pagination dots and navigation arrows.
  - Native Shopify Customizer integration supporting custom backgrounds, spacing controls, stars, and verified buyer badges.
- **Custom Section Components**: High-fidelity modular sections built with semantic HTML5 and clean CSS styling.

## Installation

### Method 1: Uploading Zip to Shopify Admin
1. ZIP the contents of the theme folder:
   ```bash
   # Ensure you ZIP from inside the directory containing layout, templates, sections, etc.
   zip -r shinepro.zip . -x "*.git*"
   ```
2. Go to your **Shopify Admin Dashboard**.
3. Navigate to **Online Store** > **Themes**.
4. Click **Add Theme** > **Upload zip file** and select `shinepro.zip`.
5. Click **Actions** > **Publish** to make ShinePro your active theme.

### Method 2: Development via Shopify CLI
To run and develop locally:
1. Ensure you have [Shopify CLI](https://shopify.dev/docs/themes/tools/cli) installed.
2. Log in to your partner account / store:
   ```bash
   shopify login --store your-store-name.myshopify.com
   ```
3. Start local development server:
   ```bash
   shopify theme dev --path .
   ```
4. Preview changes in real-time.

## Usage

### Configuring the Testimonials Carousel
1. In the Shopify Admin, click **Customize** on the ShinePro theme.
2. Click **Add Section** in the sidebar of the page where you'd like to insert the testimonials.
3. Select **Jolly Good Testimonials Slider**.
4. Customize the following settings in the inspector panel:
   - **Width Mode**: Boxed (1200px) or Full Width.
   - **Title**: Section header text.
   - **Background Color**: Hex color code picker.
   - **Spacing (Desktop & Mobile)**: Padding and margins.
5. Add individual **Testimonial Card** blocks:
   - **Quote Text**: The customer review.
   - **Author Name**: Reviewer attribution.
   - **Stars Rating**: 1-5 star selector.
   - **Verified Buyer Badge**: Show/hide checkbox.
