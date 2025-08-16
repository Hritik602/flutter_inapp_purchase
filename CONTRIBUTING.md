# Contributing to Flutter InApp Purchase

Thank you for your interest in contributing! This guide will help you get started with development and submitting your contributions.

## Getting Started

### 1. Clone the Repository

```bash
git clone https://github.com/hyochan/flutter_inapp_purchase.git
cd flutter_inapp_purchase
```

### 2. Install Dependencies

```bash
flutter pub get
```

### 3. Run the Example App

Navigate to the example directory and run the app:

```bash
cd example
flutter pub get

# For iOS
flutter run --dart-define=IOS_PRODUCTS="your_product_ids"

# For Android
flutter run --dart-define=ANDROID_PRODUCTS="your_product_ids"
```

**Note:** You'll need to configure your app with valid product IDs from your App Store Connect or Google Play Console.

## Making Changes

### 1. Fork the Repository

1. Go to <https://github.com/hyochan/flutter_inapp_purchase>
2. Click the "Fork" button in the top-right corner
3. Clone your fork locally:

   ```sh
   git clone https://github.com/YOUR_USERNAME/flutter_inapp_purchase.git
   cd flutter_inapp_purchase
   ```

### 2. Create a Feature Branch

```bash
git checkout -b feature/your-feature-name
```

### 3. Make Your Changes

- Write your code following the project conventions
- Add tests for new functionality
- Update documentation as needed

### 4. Test Your Changes

```bash
# Format your code
dart format .

# Run tests
flutter test

# Run the example app to verify functionality
cd example
flutter run
```

### 5. Commit Your Changes

```bash
git add .
git commit -m "feat: add your feature description"
```

Follow conventional commit messages:

- `feat:` for new features
- `fix:` for bug fixes
- `docs:` for documentation changes
- `refactor:` for code refactoring
- `test:` for test additions/changes
- `chore:` for maintenance tasks

### 6. Push to Your Fork

```bash
git push origin feature/your-feature-name
```

### 7. Create a Pull Request

1. Go to your fork on GitHub
2. Click "Pull request" button
3. Select your branch and target `main` branch of the original repository
4. Fill in the PR template with:
   - Description of changes
   - Related issue number (if applicable)
   - Testing performed
5. Submit the pull request

## Development Guidelines

### Coding Standards

Please refer to [CLAUDE.md](./CLAUDE.md) for:

- Naming conventions
- Platform-specific guidelines
- API method naming
- OpenIAP specification compliance

### Before Submitting

- [ ] Code is formatted with `dart format .`
- [ ] All tests pass with `flutter test`
- [ ] Example app runs without errors
- [ ] Documentation is updated if needed
- [ ] Commit messages follow conventional format

## Questions or Issues?

- For new feature proposals, start a discussion at: <https://github.com/hyochan/openiap.dev/discussions>
- For bugs, open an issue with a clear description and reproduction steps
- For questions, feel free to open a discussion

Thank you for contributing!
