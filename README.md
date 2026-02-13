# Tube Cutting Calculator

A production-optimized tube cutting calculator designed for metal fabrication shops. This tool helps calculate material requirements, optimize tube usage, and minimize waste when cutting multiple parts from stock length tubing.

## Features

- **Multi-Quantity Calculations**: Calculate material needs for multiple assembly quantities simultaneously
- **Smart Cutoff Management**: Automatically uses cutoffs from longer parts to cut shorter parts before opening new tubes
- **Production-Focused**: Optimized for speed - cuts all pieces of one length before moving to the next setup
- **Yield Analysis**: Color-coded efficiency percentages showing material usage vs. waste
- **Detailed Breakdown**: Shows exactly how many tubes are needed per part, cutoff usage, and scrap generation
- **Kerf Accounting**: Factors in saw blade kerf width for accurate material calculations

## Use Cases

Perfect for fabrication shops that need to:
- Plan material orders for production runs
- Estimate costs based on tube quantities
- Minimize waste while maintaining production efficiency
- Track yield percentages across different assembly quantities

## How It Works

1. **Enter Assembly Quantities**: Specify how many assemblies you need (e.g., 2, 25, 50, 100)
2. **Set Stock Configuration**: Define your stock tube length and saw kerf width
3. **Add Parts**: List all the parts in your assembly with their cut lengths and quantities per assembly
4. **Calculate**: The tool will:
   - Sort parts longest to shortest (for production efficiency)
   - Cut all pieces of each length
   - Use remaining cutoffs for shorter parts when possible
   - Show total tubes needed, yield percentage, and detailed breakdown

## Example

For an assembly with:
- 2× 16.75" legs
- 2× 28" legs  
- 1× 36" seat
- 1× 28" back

From 240" stock with 0.125" kerf, the calculator will determine:
- Exact tube quantities for 2, 25, 50, or 100 assemblies
- How cutoffs from cutting seats can be used for legs
- Total scrap generation grouped by size
- Material yield percentage for each quantity

## Technology

- Pure HTML/CSS/JavaScript
- No dependencies or build process required
- Runs entirely in the browser
- Mobile responsive design

## Deployment

This is a static site that can be hosted on any static hosting platform like Render, Netlify, Vercel, or GitHub Pages.

## License

Open source - free to use and modify for your production needs.
