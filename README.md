# Influencer marketing_social_media_MMM
# Social Media Impact in Marketing Mix Models: Advanced Analytical Framework

## Abstract

This repository presents an advanced Marketing Mix Modeling (MMM) framework that specifically addresses the unique dynamics of social media and influencer marketing channels. Traditional MMM approaches often fail to capture the complex effects of digital and social channels, treating them with the same adstock and saturation models used for traditional media. Our framework extends classical MMM methodology by incorporating viral coefficients, network effects, and authenticity factors that more accurately represent how social and influencer marketing operate in the modern digital ecosystem.

The analysis demonstrates that social media and influencer marketing exhibit significantly different ROI patterns and response curves compared to traditional channels. Our findings suggest that these channels benefit from higher base effectiveness but require specialized modeling approaches to accurately measure their impact. The framework also quantifies synergistic effects between digital, social, and influencer marketing, providing marketers with actionable insights for optimal budget allocation.

## Key Features

- **Extended Adstock Models**: Specialized adstock transformations for social media (short memory) and influencer channels (medium memory)
- **Viral Effects Modeling**: Captures organic reach and content spread in social media
- **Network Effect Quantification**: Models how consistent social media spend creates compounding impact
- **Authenticity Factors**: Non-linear modeling for influencer marketing effectiveness
- **Channel Interaction Analysis**: Cross-channel synergies between digital, social, and influencer channels
- **Comprehensive Visualization Suite**: Response curves, ROI comparisons, and budget optimization tools

## Framework Comparison

| Feature | Traditional MMM | Our Advanced Social Media MMM |
|---------|-----------------|-------------------------------|
| **Adstock Modeling** | Same approach for all channels | Tailored adstock parameters by channel type |
| **Effectiveness Measurement** | Linear effectiveness | Differentiated base effectiveness |
| **Digital/Social Dynamics** | Treated same as traditional | Specialized viral and network effects |
| **Influencer Impact** | Not specifically modeled | Authenticity and consistency effects |
| **Cross-Channel Effects** | Limited or none | Explicit interaction modeling |
| **Optimization** | Basic response curve | Multi-dimensional simulation |

## Visualization Examples

The repository includes advanced visualization tools to understand channel performance:

- Channel Response Curves: Non-linear effects across different spend levels
- ROI Comparison: Direct measurement of return across all channels
- Media Spend Patterns: Temporal analysis of spending effectiveness
- Sales Decomposition: Attribution of sales to each marketing channel
- Budget Optimization: Optimal allocation recommendations based on simulations

## Getting Started

### Prerequisites

- Python 3.8+
- Required packages: numpy, pandas, scikit-learn, statsmodels, plotly

### Installation

```bash
git clone https://github.com/viznuv/influencer_social_media_MMM.git
cd influencer_social_media_MMM
pip install -r requirements.txt
```

### Basic Usage

```python
from marketing_mix_model import run_mmm_analysis

# Run the complete analysis with your data
results = run_mmm_analysis(periods=104, train_model=True, visualize=True)

# Access key results
roi_results = results['roi_results']
simulation_results = results['simulation_results']

# Save visualizations
from visualization_utils import save_mmm_visualizations
save_mmm_visualizations(results)
```

## Key Findings

1. **Social Media ROI Dynamics**: Social media channels show higher base effectiveness (2.5x) but shorter retention (0.2 adstock) compared to traditional channels.

2. **Viral Coefficient Impact**: Viral effects account for approximately 15-20% of total social media impact when properly modeled.

3. **Authenticity Factor**: Influencer marketing shows a non-linear relationship between spend and effectiveness, with moderate spend levels sometimes outperforming higher spend.

4. **Channel Synergies**: Digital and social media channels exhibit substantial positive interaction effects (up to 30% lift when used together strategically).

5. **Optimal Budget Allocation**: Simulations typically suggest higher allocation to social and influencer channels than traditional MMM approaches.

## Contributing

Contributions are welcome! Please feel free to submit a Pull Request.

## License

This project is licensed under the MIT License - see the LICENSE file for details.

## Citation

If you use this framework in your research or project, please cite:

```
@software{social_media_mmm_2025,
  author = {Vishnu Prasad V},
  title = {Social Media Impact in Marketing Mix Models: Advanced Analytical Framework},
  year = {2025},
  url = {https://github.com/viznuv/social-media-mmm}
}
```

