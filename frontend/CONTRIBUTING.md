# Contributing to Universal Deep Research Frontend

This code details a research and demonstration prototype. This software is not intended for production use.

## How to Contribute

### 1. Fork and Clone

```bash
git clone <your-fork-url>
cd frontend
```

### 2. Set Up Development Environment

```bash
npm install
# or
yarn install
```

### 3. Make Changes

- Follow existing code style and patterns
- Add tests for new functionality
- Update documentation as needed
- Ensure all TODO comments are addressed or documented

### 4. Testing

- Test components manually in development mode
- Verify UI changes work correctly across different screen sizes
- Ensure accessibility standards are maintained

### 5. Submit Pull Request

- Create a descriptive PR title
- Include clear description of changes
- Ensure code follows research/demonstration focus

## Code Standards

- **TypeScript**: Follow TypeScript best practices and strict mode
- **React**: Use functional components with hooks
- **Next.js**: Follow Next.js 13+ App Router conventions
- **CSS**: Use CSS modules for component styling
- **Documentation**: Use clear JSDoc comments and inline documentation
- **Error Handling**: Implement proper error boundaries and error states
- **Configuration**: Use environment variables for customization
- **Accessibility**: Follow WCAG guidelines and use semantic HTML

## Development Commands

```bash
# Start development server
npm run dev
# or
yarn dev

# Build for production
npm run build
# or
yarn build

# Run linting
npm run lint
# or
yarn lint

# Run type checking
npm run type-check
# or
yarn type-check
```

## License

By contributing, you agree that your contributions will be licensed under the same terms as this project (research/demonstration use only). You can find the license in [LICENSE](../LICENSE.txt).

#### Signing Your Work

- We require that all contributors "sign-off" on their commits. This certifies that the contribution is your original work, or you have rights to submit it under the same license, or a compatible license.

  - Any contribution which contains commits that are not Signed-Off will not be accepted.

- To sign off on a commit you simply use the `--signoff` (or `-s`) option when committing your changes:

  ```bash
  $ git commit -s -m "Add cool feature."
  ```

  This will append the following to your commit message:

  ```
  Signed-off-by: Your Name <your@email.com>
  ```

- Full text of the DCO:

  ```
    Developer Certificate of Origin
    Version 1.1

    Copyright (C) 2004, 2006 The Linux Foundation and its contributors.
    1 Letterman Drive
    Suite D4700
    San Francisco, CA, 94129

    Everyone is permitted to copy and distribute verbatim copies of this license document, but changing it is not allowed.
  ```

  ```
    Developer's Certificate of Origin 1.1

    By making a contribution to this project, I certify that:

    (a) The contribution was created in whole or in part by me and I have the right to submit it under the open source license indicated in the file; or

    (b) The contribution is based upon previous work that, to the best of my knowledge, is covered under an appropriate open source license and I have the right under that license to submit that work with modifications, whether created in whole or in part by me, under the same open source license (unless I am permitted to submit under a different license), as indicated in the file; or

    (c) The contribution was provided directly to me by some other person who certified (a), (b) or (c) and I have not modified it.

    (d) I understand and agree that this project and the contribution are public and that a record of the contribution (including all personal information I submit with it, including my sign-off) is maintained indefinitely and may be redistributed consistent with this project or the open source license(s) involved.
  ```
