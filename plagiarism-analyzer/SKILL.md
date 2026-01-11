# Plagiarism and Originality Analyzer Skill

This skill enables comprehensive analysis of text content to assess originality, verify citations, and detect potential plagiarism.

## Features

- **Citation Verification**: Checks if quoted material is properly attributed
- **Originality Scoring**: Calculates a percentage score (1-100%) representing content originality
- **Final Verdict**: Provides a classification (Original, Synthesized, or Copied)
- **Detailed Reporting**: Offers specific feedback on potential issues
- **Academic Integrity Assessment**: Evaluates content against academic standards

## How to Use

1. Activate the Plagiarism and Originality Analyzer skill
2. Provide the text or document to analyze
3. Receive a comprehensive report with:
   - Citation check results
   - Originality score (1-100%)
   - Final verdict classification
   - Specific recommendations for improvement

## Analysis Categories

- **Original (85-100%)**: Content is primarily authored by submitter with proper attribution
- **Synthesized (60-84%)**: Combines original work with properly cited external sources
- **Copied (Below 60%)**: Contains substantial portions from external sources without attribution

## Skill Components

- `SKILL.md`: Main skill definition and capabilities
- `references/analysis_guide.md`: Detailed methodology for plagiarism detection
- `scripts/sample_analyses.md`: Examples of how to apply the analysis framework

## Limitations

- Cannot access real-time web content for comparison
- Relies on pattern recognition rather than database searches
- Accuracy may vary based on content type and length
- Cannot definitively prove plagiarism, only identify potential issues
