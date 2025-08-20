# World Clock Dashboard

A beautiful, responsive world clock application that displays time across multiple timezones with both analog and digital views.

![World Clock](https://animeshkumarrai.github.io/World_Clock)

## Features

- **Analog Clock**: A visually appealing analog clock with smooth hand movements
- **Digital Clock**: Large, easy-to-read digital display with date and timezone information
- **Multiple Timezones**: Track time across different timezones around the world
- **Interactive Cards**: Click on any timezone card to set it as the main clock
- **Add/Remove Timezones**: Easily add or remove timezones from your dashboard
- **Responsive Design**: Works seamlessly on desktop, tablet, and mobile devices
- **Real-time Updates**: All clocks update every second to ensure accuracy

## Technologies Used

- **HTML5**: Semantic markup for structure
- **Tailwind CSS**: Utility-first CSS framework for styling
- **Font Awesome**: Icon library for UI elements
- **Vanilla JavaScript**: For all functionality and interactivity

## Installation

1. Clone this repository:
   ```bash
   git clone https://AnimeshKumarRai/your-username/World_Clock.git
   ```

2. Navigate to the project directory:
   ```bash
   cd world-clock-dashboard
   ```

3. Open `index.html` in your preferred web browser.

## Usage

1. The main clock displays the selected timezone by default (UTC).
2. Use the dropdown menu to change the main timezone.
3. Click on any timezone card to set it as the main clock.
4. Add new timezones using the "Add Another Timezone" section.
5. Remove timezones by clicking the × button on any card.
6. Use the refresh button to manually update all clocks.

## Customization

### Adding Timezones

To add more timezones, modify the `timezones` array in the JavaScript section:

```javascript
const timezones = [
    // Existing timezones...
    { id: 'Asia/Seoul', name: 'Seoul (KST)' },
    { id: 'America/Mexico_City', name: 'Mexico City (CST)' }
    // Add more as needed
];
```

### Styling

Customize the appearance by modifying the CSS in the `<style>` section or by overriding Tailwind classes in the HTML elements.

## Browser Compatibility

This application works on all modern browsers, including:
- Chrome (latest)
- Firefox (latest)
- Safari (latest)
- Edge (latest)

## Contributing

Contributions are welcome! If you have suggestions for improvements or new features, please open an issue or submit a pull request.


## Acknowledgments

- Timezone data provided by the IANA Time Zone Database
- Icons from Font Awesome
- Styling with Tailwind CSS

---

Made with ❤️ by [AnimeshKumarRai](https://github.com/AnimeshKumarRai)
