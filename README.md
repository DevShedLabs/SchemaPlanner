# SchemaPlanner

A modern web-based tool for designing, visualizing, and converting between different schema formats. SchemaPlanner helps developers and database architects quickly prototype data structures and export them to various formats including TypeScript interfaces, JSON Schema, and SQL.

## Features

- **Visual Schema Designer**
    - Intuitive field creation and management
    - Support for common data types
    - Required/optional field toggling
    - Default value specification
    - Field descriptions for documentation

- **Reverse Engineering**
    - Import existing JSON data
    - Parse JSON Schema definitions
    - Automatic type inference
    - Nested object support with dot notation
    - Smart default value detection

- **Multiple Export Formats**
    - TypeScript interfaces
    - JSON Schema
    - SQL CREATE TABLE statements
    - More formats coming soon...


### Usage

1. **Creating a Schema**
    - Click "Add Field" to create new fields
    - Fill in field details: name, type, default value, and description
    - Toggle required/optional status as needed
    - Remove fields using the trash icon

2. **Reverse Engineering**
    - Paste existing JSON or JSON Schema into the input area
    - Click "Generate Fields" to automatically create fields
    - Edit generated fields as needed

3. **Exporting**
    - Select desired output format from the dropdown
    - Copy the generated code from the output panel


### Technologies Used

- React
- Bootstrap
- Babel

### Contributing

1. Fork the repository
2. Create a feature branch (`git checkout -b feature/amazing-feature`)
3. Commit your changes (`git commit -m 'Add amazing feature'`)
4. Push to the branch (`git push origin feature/amazing-feature`)
5. Open a Pull Request

## Roadmap

- [ ] Additional output formats (Mongoose, Prisma, etc.)
- [ ] Schema validation rules
- [ ] Schema version control
- [ ] Custom type definitions

## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

## Support

For support, feature requests, or bug reports, please open an issue on the [GitHub repository](https://github.com/DevShedLabs/SchemaPlanner/issues).

---

Made with ♥ by DevShedLabs