# Responsive Testimonial Slider

A modern, responsive testimonial slider built with HTML, CSS, and Swiper.js. This slider showcases client testimonials with a clean, professional design that works seamlessly across mobile, tablet, and desktop devices.

## Screenshots & Demo

### Video Demo

<div align="center">
  <a href="screenshots/vdooo.mp4">
    <img src="screenshots/desktop-view.jpg" alt="Desktop View Demo" width="70%">
  </a>
  <p><em>Click the image above to view the desktop demo video</em></p>

  <a href="screenshots/testimonial-slider-mobile-demo.mp4">
    <img src="screenshots/mobile-view.jpg" alt="Mobile View Demo" width="30%">
  </a>
  <p><em>Click the image above to view the mobile demo video</em></p>
</div>

### Desktop View

![Desktop View](screenshots/desktop-view.jpg)

On desktop, the slider displays three testimonials simultaneously, providing a comprehensive view of client feedback at a glance.

## Features

- **Responsive Design**: Adapts perfectly to all screen sizes (mobile, tablet, desktop)
- **Auto-Sliding**: Automatically cycles through testimonials
- **Navigation Controls**: Includes arrow buttons and pagination dots
- **Smooth Transitions**: Professional animations between slides
- **Modern UI**: Clean, card-based design with hover effects
- **Customizable**: Easily modify colors, content, and behavior

## Technologies Used

- HTML5
- CSS3
- JavaScript
- [Swiper.js](https://swiperjs.com/) - Modern mobile touch slider

## Demo

View the live demo by opening the `index.html` file in your browser.

## Usage

1. Clone or download this repository
2. Open `index.html` in your web browser
3. The slider will automatically start cycling through testimonials

## Customization

### Changing Testimonials

Edit the HTML in `index.html` to update testimonial content:

```html
<div class="swiper-slide">
    <div class="testimonial-card">
        <div class="testimonial-img">
            <img src="your-image-url.jpg" alt="Client Name">
        </div>
        <div class="testimonial-content">
            <h3>Client Name</h3>
            <div class="stars">
                <span>★</span><span>★</span><span>★</span><span>★</span><span>★</span>
            </div>
            <p>"Your testimonial text here..."</p>
        </div>
    </div>
</div>
```

### Styling

Modify the `styles.css` file to change colors, spacing, and other visual elements.

### Slider Settings

Adjust the Swiper.js configuration in `script.js` to change:

- Slide speed
- Autoplay delay
- Number of visible slides
- Transition effects
- And more

```javascript
const swiper = new Swiper('.swiper', {
    // Modify settings here
    speed: 800,
    autoplay: {
        delay: 5000,
    },
    // Other settings...
});
```

## Responsive Behavior

### Desktop View

![Desktop View](screenshots/desktop-view.jpg)

On larger screens, the slider displays three testimonials simultaneously for a comprehensive overview.

### Mobile View

![Mobile View](screenshots/mobile-view.jpg)

On mobile devices, the slider displays one testimonial at a time for optimal readability and user experience.

### Tablet View

On tablets, the slider shows two testimonials side by side, balancing content density and readability.

## Browser Support

- Chrome
- Firefox
- Safari
- Edge
- Opera

## License

This project is available for personal and commercial use.

## Credits

- Profile images from [Random User API](https://randomuser.me/)
- Slider functionality powered by [Swiper.js](https://swiperjs.com/)
