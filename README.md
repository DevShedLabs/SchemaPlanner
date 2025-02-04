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

## Getting Started

### Prerequisites

- Node.js (v18 or higher)
- npm or yarn

### Installation

```bash
# Clone the repository
git clone git@github.com:DevShedLabs/SchemaPlanner.git

# Navigate to project directory
cd SchemaPlanner

# Install dependencies
npm install

# Start development server
npm run dev
```

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

## Development

### Project Structure

```
SchemaPlanner/
├── src/
│   ├── components/
│   │   ├── SchemaPlanner/
│   │   └── ui/
│   ├── lib/
│   └── app/
├── public/
└── ...
```

### Technologies Used

- React
- TypeScript
- Tailwind CSS
- shadcn/ui
- Lucide Icons

### Contributing

1. Fork the repository
2. Create a feature branch (`git checkout -b feature/amazing-feature`)
3. Commit your changes (`git commit -m 'Add amazing feature'`)
4. Push to the branch (`git push origin feature/amazing-feature`)
5. Open a Pull Request

## Roadmap

- [ ] Additional output formats (Mongoose, Prisma, etc.)
- [ ] Schema validation rules
- [ ] Import from database connection
- [ ] Schema version control
- [ ] Team collaboration features
- [ ] Custom type definitions

## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

## Acknowledgments

- Inspired by the need for better schema design tools in modern web development
- Built with love by DevShedLabs
- Special thanks to all contributors and the open-source community

## Support

For support, feature requests, or bug reports, please open an issue on the [GitHub repository](https://github.com/DevShedLabs/SchemaPlanner/issues).

---

Made with ♥ by DevShedLabs