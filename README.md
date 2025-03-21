# Remote Job Finder

This is an Angular web application that allows users to search for remote jobs across various industries. It integrates job listing APIs and presents results with filtering options to help users find their ideal remote work opportunities.

## Features

- 🔍 **Search Jobs:** Users can search by keyword, category, or company.
- 🎯 **Filter Results:** Filter by job type (full-time, part-time, contract, etc.) and location (remote-only).
- 💾 **Save Favorites:** Save jobs for later viewing.
- 🌐 **API Integration:** Pulls job listings from popular job boards.
- 🌓 **Dark Mode:** Supports light and dark themes.

## Technologies Used

- **Angular** (v15+)
- **TypeScript**
- **RxJS** for reactive programming
- **Bootstrap** (or Tailwind CSS) for styling
- **Axios** or **HttpClient** for API calls
- **Firebase** (optional) for user authentication and data storage

## Getting Started

### Prerequisites

- Node.js & npm installed
- Angular CLI installed globally

### Installation

1. Clone the repo:
    ```bash
    git clone https://github.com/yourusername/remote-job-finder.git
    cd remote-job-finder
    ```

2. Install dependencies:
    ```bash
    npm install
    ```

3. Add environment variables:
    Create `src/environments/environment.ts` and `src/environments/environment.prod.ts` files with your API keys and configuration.

    Example:
    ```typescript
    export const environment = {
      production: false,
      apiUrl: 'https://api.example.com/jobs',
      firebaseConfig: { ... } // Optional Firebase config
    };
    ```

4. Run the development server:
    ```bash
    ng serve
    ```

   The app will be available at `http://localhost:4200/`

### Build for Production

```bash
ng build --prod
```

## Future Improvements

- 🌟 **Job Alerts:** Notify users about new listings matching their search criteria.
- 💼 **User Profiles:** Allow users to manage saved jobs and preferences.
- 🌍 **Localization:** Multi-language support.

## Contributing

Pull requests are welcome! For major changes, please open an issue first to discuss what you'd like to improve.

## License

[MIT](LICENSE)

---

Happy job hunting! 🚀
