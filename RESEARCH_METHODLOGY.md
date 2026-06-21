# Academic Research Methodology & Literature Search Notes

## Search Strategy

### Tools Available:
- **Context7 Documentation Query**: For software library documentation (marketing APIs, analytics platforms)
- **GitHub Repository Search**: For finding code repositories related to marketing research
- **GitHub Code Search**: For finding implementations of marketing models
- **Agent Research Skills (lingzhi227/agent-research-skills)**: References Semantic Scholar API for peer-reviewed literature

### Limitations Encountered:
The available tools primarily access:
1. **Software documentation** (APIs, SDKs, analytics platforms)
2. **Marketing practitioner knowledge bases** (comprehensive but practitioner-oriented)
3. **Academic research workflow tools** (methodology guides, not direct paper access)

### What Was NOT Directly Accessible:
- Full-text peer-reviewed journal articles from Journal of Consumer Research, Journal of Marketing Research, etc.
- Direct Semantic Scholar API queries (requires API key not available in this environment)
- Proprietary marketing research databases (Nielsen, Kantar, etc.)

## Recommended Next Steps for Deeper Research:

### Using Semantic Scholar API:
```bash
# Search for peer-reviewed papers on AIDA and video marketing
python ~/.claude/skills/deep-research/scripts/search_semantic_scholar.py \
  --query "AIDA model video marketing short-form video attention" \
  --max-results 20 --year-range 2018-2026 --peer-reviewed-only \
  --api-key "YOUR_API_KEY"

# Search for FOMO and video advertising research
python ~/.claude/skills/deep-research/scripts/search_semantic_scholar.py \
  --query "FOMO fear missing out video advertising consumer behavior" \
  --max-results 20 --year-range 2018-2026 --peer-reviewed-only \
  --api-key "YOUR_API_KEY"
```

### Key Search Terms for Academic Databases:
1. "AIDA model" AND "video advertising" AND "attention"
2. "short-form video" AND "consumer psychology" AND "engagement"
3. "micro-AIDA" OR "fractional AIDA" AND "mobile advertising"
4. "attention capture" AND "first 3 seconds" AND "video marketing"
5. "FOMO" AND "video advertising" AND "conversion"
6. "call to action" AND "urgency" AND "video" AND "conversion rate"
7. "aspiration" AND "identity" AND "video marketing" AND "desire"
8. "neuromarketing" AND "video" AND "attention metrics"

### Target Journals:
- Journal of Consumer Research (Impact Factor: 6.8)
- Journal of Marketing Research (Impact Factor: 5.0)
- Marketing Science (Impact Factor: 4.7)
- Journal of Consumer Psychology (Impact Factor: 5.5)
- Journal of Advertising (Impact Factor: 3.5)
- Psychology & Marketing (Impact Factor: 3.2)
- Journal of Interactive Marketing (Impact Factor: 8.2)
- Internet Research (Impact Factor: 4.5)

### APA 7th Citation Format for Found Videos:
```
Author, A. A. [Screen name]. (Year, Month Day). Title of video [Video]. YouTube. URL
```

## Key Researchers in This Domain:
1. **Dr. Robert Cialdini** - Psychology of influence and persuasion
2. **Dr. Daniel Kahneman** - Decision-making, behavioral economics
3. **Dr. Jonah Berger** - Social influence, word-of-mouth, viral marketing
4. **Dr. Noah Goldstein** - Persuasion and behavioral change
5. **Dr. Zakary Tormala** - Attitudes, persuasion, social influence
6. **Dr. Vanessa Bohns** - Social influence, psychology of asking
7. **Dr. Adam Grant** - Motivation and organizational psychology

## Institutions with Active Research:
- Harvard Business School
- Stanford Graduate School of Business  
- Wharton School (UPenn)
- Yale School of Management
- Northwestern Kellogg School of Management
- INSEAD
- MIT Sloan School of Management

## Research Gaps Identified:
1. Limited peer-reviewed research specifically on "fractional AIDA" as a formal concept
2. Few studies with true experimental designs isolating individual psychological techniques
3. Rapid platform evolution outpaces academic publishing cycles
4. Proprietary data from platforms (TikTok, Meta) limits independent research
5. Need for more cross-cultural validation of AIDA-based video strategies
