# Third-Party Licenses

This software uses the following third-party libraries and their respective licenses:

## Runtime Dependencies

### AWS SDK
- **@aws-sdk/client-bedrock-runtime**: Apache-2.0 License - Amazon Web Services
- **@aws-sdk/client-transcribe-streaming**: Apache-2.0 License - Amazon Web Services
- **@smithy/** (transitive): Apache-2.0 License - AWS

### React Framework
- **react**: MIT License - Meta Platforms, Inc.
- **react-dom**: MIT License - Meta Platforms, Inc.

### Editor & UI Components
- **@monaco-editor/react**: MIT License - Microsoft Corporation
- **monaco-editor**: MIT License - Microsoft Corporation
- **lucide-react**: ISC License - Lucide Contributors

### Drag and Drop
- **@dnd-kit/core**: MIT License - Claudéric Demers
- **@dnd-kit/sortable**: MIT License - Claudéric Demers
- **@dnd-kit/utilities**: MIT License - Claudéric Demers

### Markdown Processing
- **react-markdown**: MIT License - Titus Wormer
- **remark-gfm**: MIT License - Titus Wormer
- **remark-math**: MIT License - Titus Wormer
- **rehype-highlight**: MIT License - Titus Wormer
- **rehype-katex**: MIT License - Titus Wormer
- **rehype-raw**: MIT License - Titus Wormer
- **mermaid**: MIT License - Knut Sveidqvist

### Auto-Update
- **electron-updater**: MIT License - Electron Userland

### Network & Proxy
- **http-proxy-agent**: MIT License - Nathan Rajlich
- **https-proxy-agent**: MIT License - Nathan Rajlich
- **node-fetch**: MIT License - David Frank

### Utilities
- **uuid**: MIT License (transitive dependency)
- **fast-xml-parser**: MIT License (transitive dependency)

## Development Dependencies

### Build Tools
- **vite**: MIT License - Evan You
- **@vitejs/plugin-react**: MIT License
- **electron**: MIT License - Electron contributors
- **electron-builder**: MIT License - Stefan Judis
- **sharp**: Apache-2.0 License - Lovell Fuller
- **typescript**: Apache-2.0 License - Microsoft Corporation

### Development Utilities
- **concurrently**: MIT License
- **cross-env**: MIT License

---

## License Compatibility

All third-party licenses are compatible with the MIT License used by this project:

- **MIT License**: Same license as main project, fully compatible
- **ISC License**: Fully compatible, similar permissive terms
- **Apache License 2.0**: Compatible, requires preservation of notices

## Full License Texts

For complete license texts of each library, please refer to their respective repositories or npm package information using:

```bash
npm info [package-name] license
npm info [package-name] repository
```

---

**Note**: This file lists major dependencies. For a complete list of all transitive dependencies and their licenses, run `npm list` in the project directory.
