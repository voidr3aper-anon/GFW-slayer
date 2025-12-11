# V2Ray Configuration Organization

## Structure

```
configs/
├── regional/           # Region-specific optimized configurations
│   ├── china/         # Configurations optimized for China
│   ├── iran/          # Configurations optimized for Iran  
│   └── russia/        # Configurations optimized for Russia
├── general/           # General-purpose configurations
└── README.md          # This file
```

## For Existing Users

**IMPORTANT**: All original configuration files remain in the root directory to maintain existing subscription URLs. The new organized structure in `configs/` is for better management and future updates.

### Stable URLs (won't change):
- `https://raw.githubusercontent.com/voidr3aper-anon/GFW-slayer/main/serverless-china-friendly.json`
- `https://raw.githubusercontent.com/voidr3aper-anon/GFW-slayer/main/serverless-iran-freindly.json`
- `https://raw.githubusercontent.com/voidr3aper-anon/GFW-slayer/main/serverless-russia-friendly.json`
- `https://raw.githubusercontent.com/voidr3aper-anon/GFW-slayer/main/serverless-v2ray.json`
- `https://raw.githubusercontent.com/voidr3aper-anon/GFW-slayer/main/V-force.json`

## For New Users

You can now find configurations organized by region in the `configs/` directory for easier browsing and selection.

## Maintenance

- Root directory files are the production versions that users subscribe to
- `configs/` directory contains organized copies for development and management
- When updating configurations, make sure to update both locations