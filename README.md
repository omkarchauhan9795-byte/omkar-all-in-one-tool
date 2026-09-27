# OmkarTools All in one

A comprehensive, free online tools platform built with Next.js 14, TypeScript, and Tailwind CSS. Features 45+ tools for file conversion, image processing, calculations, document generation, and more.

## Features

- **45+ Free Tools** - All tools work completely offline in your browser
- **Privacy First** - No file uploads, no tracking, no registration required
- **Responsive Design** - Works on desktop, tablet, and mobile
- **Dark Mode** - System-aware dark/light theme with manual toggle
- **SEO Optimized** - Proper metadata, sitemap, and structured data
- **Fast Performance** - Static generation with minimal JavaScript

## Tool Categories

### File & PDF Tools (10)
- JPG to PDF Converter
- PNG to JPG Converter
- JPG to PNG Converter
- WebP to JPG Converter
- Image to WebP Converter
- PDF Merger
- Image Compressor
- Image Resizer
- File Size Converter
- PDF to JPG Converter

### Image Tools (3)
- Image Cropper
- Image Rotator
- Image Dimensions Checker

### Resume & Documents (2)
- Resume Builder (3 templates)
- Invoice Generator

### Calculators (9)
- Percentage Calculator
- Age Calculator
- EMI Calculator
- GST Calculator
- Discount Calculator
- Profit/Loss Calculator
- BMI Calculator
- Average Calculator
- Ratio Calculator

### Converters (6)
- Length Converter
- Weight Converter
- Temperature Converter
- Area Converter
- Volume Converter
- Data Storage Converter

### Text Tools (4)
- Word Counter
- Case Converter
- Remove Extra Spaces
- Text Sorter

### Developer Tools (6)
- JSON Formatter
- JSON to CSV
- CSV to JSON
- Base64 Encoder/Decoder
- URL Encoder/Decoder
- UUID Generator

### Generators (3)
- Password Generator
- QR Code Generator
- Random Number Generator

### Date & Time (2)
- Date Difference Calculator
- Days Calculator

## Tech Stack

- **Framework**: Next.js 14 (App Router)
- **Language**: TypeScript
- **Styling**: Tailwind CSS
- **Icons**: Lucide React
- **PDF**: pdf-lib, jsPDF, html2canvas
- **QR Code**: qrcode
- **CSV**: PapaParse
- **ZIP**: jszip

## Getting Started

### Prerequisites
- Node.js 18+
- npm or yarn

### Installation

```bash
# Clone the repository
git clone <repository-url>
cd omkartools

# Install dependencies
npm install

# Start development server
npm run dev
```

Open [http://localhost:3000](http://localhost:3000) in your browser.

### Production Build

```bash
npm run build
npm start
```

## Project Structure

```
omkartools/
├── app/                    # Next.js App Router pages
│   ├── [toolSlug]/         # Dynamic tool pages
│   ├── categories/         # Category listing pages
│   ├── tools/              # All tools listing
│   ├── popular/            # Popular tools page
│   ├── about/              # About page
│   ├── contact/            # Contact page
│   ├── privacy/            # Privacy policy
│   └── terms/              # Terms of service
├── components/
│   ├── layout/             # Layout components (Header, Footer, etc.)
│   ├── tools/              # Individual tool components
│   ├── ui/                 # Reusable UI components
│   └── providers/          # Context providers (Theme)
├── lib/
│   ├── tools/              # Tool registry and utilities
│   ├── seo.ts              # SEO metadata generation
│   ├── site-config.ts      # Site configuration
│   └── utils.ts            # Utility functions
├── types/
│   └── tool.ts             # TypeScript types
├── public/                 # Static assets
├── .eslintrc.json          # ESLint configuration
├── next.config.mjs         # Next.js configuration
├── tailwind.config.ts      # Tailwind CSS configuration
├── tsconfig.json           # TypeScript configuration
└── package.json            # Dependencies and scripts
```

## Adding a New Tool

1. Create the tool component in `components/tools/ToolName.tsx`
2. Add the tool to `lib/tools/registry.ts`
3. The tool will automatically appear in:
   - Homepage featured/popular sections
   - Category pages
   - All tools listing
   - Search results
   - Related tools suggestions
   - Sitemap

## Deployment

### Vercel (Recommended)

1. Push to GitHub
2. Import project in Vercel
3. Deploy automatically

### Other Platforms

```bash
npm run build
npm start
```

## Privacy

- All processing happens locally in your browser
- No files are uploaded to any server
- No personal data is collected
- No cookies or tracking
- Works offline once loaded

## Contributing

1. Fork the repository
2. Create a feature branch
3. Make your changes
4. Run `npm run build` and `npm run lint`
5. Submit a pull request

## License

MIT License - Free to use, modify, and distribute.

## Support

- GitHub Issues: Report bugs or request features
- Email: hello@omkartools.example.com# omkar-all-in-one-tool
# omkar-all-in-one-tool
# omkar-all-in-one-tool
