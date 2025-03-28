# Outhad Search

## Re-defining e-commerce search experiences

Outhad Search provides powerful AI based search engine solutions for e-commerce platforms, helping businesses deliver exceptional search experiences to their customers.

## ✨ Features

- **AI based Search Engine**: Ai based sematic and vector search capabilities
- **High-Performance Search Engine**: Fast and accurate search results for your e-commerce catalog
- **Easy Integration**: Simple APIs and SDKs for seamless integration
- **Advanced Filters**: Enable customers to narrow down search results effectively
- **Typo Tolerance**: Find relevant results even when users make typos
- **Custom Ranking**: Prioritize results based on your business rules
- **Analytics Dashboard**: Understand search patterns and optimize your catalog

## 🚀 Getting Started

### Using our JavaScript SDK

```bash
npm install outhadsearch-sdk-js
```

Check out our [SDK repository](https://github.com/Outhad-Search/outhadsearch-sdk-js) for detailed documentation and examples.

### CLI Tool

Our SDK includes a powerful CLI tool for managing your search indices:

```bash
# Configure the CLI
outhadsearch config set --host http://your-outhadsearch-host:7700 --api-key your-api-key

# List available indexes
outhadsearch indexes list

# Create a new index
outhadsearch indexes create my-index --primary-key id

# Add documents from a JSON file
outhadsearch documents add my-index --file data.json

# Search documents
outhadsearch search my-index "search query" --highlight
```

## 📚 Resources

- [Website](https://outhad.com)
- [Documentation](https://outhad.com/docs)
- [NPM Package](https://www.npmjs.com/package/outhadsearch-sdk-js)
- [GitHub Repository](https://github.com/Outhad-Search/outhadsearch-sdk-js)

## 🤝 Connect With Us

- [LinkedIn](https://www.linkedin.com/company/outhadai/)

## 📄 License

Our SDKs and examples are released under the [MIT License](https://github.com/Outhad-Search/outhadsearch-sdk-js/blob/main/LICENSE).
