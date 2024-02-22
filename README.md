# Empress SCS Sales Purchase: Transform Your Sales and Purchase Operations ![Empress SCS Sales Purchase Logo](https://grow.empress.eco/uploads/default/original/2X/1/1f1e1044d3864269d2a613577edb9763890422ab.png

Welcome to **Empress SCS Sales Purchase**, your ultimate tool for efficient and streamlined sales and purchase management in Empress. Ideal for businesses seeking to upgrade their selling and buying processes, our solution eliminates manual, time-consuming tasks, paving the way for improved business operations. 

Explore our [Documentation](https://grow.empress.eco/) for in-depth insights or report a bug and request a feature through our [Issues Page](https://github.com/empress-eco/scs_sales_purchase/issues).

## About Empress SCS Sales Purchase

### Overview 📖
Built to seamlessly integrate with Empress, Empress SCS Sales Purchase is a powerful tool designed to revolutionize your sales and purchase operations. 

### Key Features 🌟
- Default Supplier to create Purchase Order
- Item-wise custom Supplier with create Purchase Order

## Technical Stack and Setup Instructions

### Prerequisites
Before installing, ensure you have the following modules installed in your Empress:
- Selling
- Buying

### Installation
Get Empress SCS Sales Purchase up and running in your Empress with these easy steps:

```sh
# Clone the repository
git clone https://github.com/empress-eco/scs_sales_purchase.git

# Navigate to the project directory
cd scs_sales_purchase

# For Version 13
bench get-app scs_sales_purchase
# For Version 14
bench get-app scs_sales_purchase --branch 14.0

# Install the app
bench --site [your.site.name] install-app scs_sales_purchase

# Migrate and clear cache
bench migrate
bench clear-cache
```

## Usage
After installation, Empress SCS Sales Purchase is ready to revolutionize your sales and purchase operations. Visit our [documentation](https://grow.empress.eco/) for a detailed usage guide.

## Contribution Guidelines
We welcome and appreciate contributions that can enhance Empress SCS Sales Purchase. Here's how you can contribute:

- Fork the Project
- Create your Feature Branch (`git checkout -b feature/AmazingFeature`)
- Commit your Changes (`git commit -m 'Add some AmazingFeature'`)
- Push to the Branch (`git push origin feature/AmazingFeature`)
- Open a Pull Request

## License and Acknowledgments

### License
This project is under the [MIT License](https://opensource.org/licenses/MIT). Your contributions are also licensed under the MIT License.

### Acknowledgments
We express profound gratitude to the Empress Community for their foundational contributions that form the backbone of this project. Their innovation and dedication have been instrumental in building the functionalities we rely on. We are immensely thankful for their pioneering work and ongoing support.