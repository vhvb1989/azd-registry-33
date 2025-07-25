# Azure Developer CLI (azd) Extensions Registry

This repository contains the official registry for Azure Developer CLI (azd) extensions. The registry serves as a central location where developers can discover and access community-contributed azd extensions.

## What are azd Extensions?

Azure Developer CLI extensions are tools that extend the functionality of azd, allowing developers to customize and enhance their development workflow with Azure. Extensions can provide additional commands, templates, and integrations to streamline cloud development processes.

## Contributing Your Extension

We welcome contributions from the community! If you've developed an azd extension that you'd like to share with other developers, you can submit it to this registry.

### How to Submit Your Extension

1. **Fork this repository**
2. **Edit the `registry.json` file** to include your extension details
3. **Create a Pull Request** with your changes

### Extension Requirements

Before submitting your extension, please ensure it meets the following criteria:

- ✅ The extension is functional and well-tested
- ✅ Includes proper documentation (README, usage examples)
- ✅ Follows azd extension development best practices
- ✅ Has a clear license (preferably open source)
- ✅ Provides value to the azd community

### Registry Format

Extensions are listed in the `registry.json` file. Each entry should include:

```json
{
  "name": "your-extension-name",
  "description": "Brief description of what your extension does",
  "author": "Your Name or Organization",
  "repository": "https://github.com/your-username/your-extension-repo",
  "version": "1.0.0",
  "tags": ["tag1", "tag2"],
  "license": "MIT"
}
```

## Using Extensions from this Registry

To discover and install extensions from this registry, refer to the [Azure Developer CLI documentation](https://docs.microsoft.com/azure/developer/azure-developer-cli/) for the latest instructions on extension management.

## Support and Issues

If you encounter issues with:
- **A specific extension**: Please report issues directly to the extension's repository
- **The registry itself**: Open an issue in this repository

## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

## Community Guidelines

Please be respectful and constructive in all interactions. We're building this registry together to benefit the entire Azure developer community.

---

Happy coding! 🚀
