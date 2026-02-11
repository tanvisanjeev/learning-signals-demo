# Learning Signals - Educational Transcript Analysis

🎓 AI-powered pattern discovery for qualitative learning data

## Overview
A browser-based tool for analyzing interview transcripts and learning reflections at scale. Designed for educational researchers who need to process large volumes of qualitative data.

## Features
- **Batch Upload**: Handle multiple CSV files or sample data
- **Pattern Detection**: TF-IDF + K-means clustering
- **AI Analysis**: Claude-powered educational interpretations
- **Scalable Design**: Built for 100s-1000s of transcripts
- **Research Ethics**: Non-evaluative, transparent methodology

## Live Demo
🔗 [Try it live](https://learning-signals-demo.vercel.app)

## Use Cases
- Student reflection analysis
- Interview transcript processing  
- Course feedback synthesis
- Voice AI interview data analysis

## Technical Approach
- **Vectorization**: TF-IDF for semantic representation
- **Clustering**: K-means for pattern grouping
- **Interpretation**: Claude API for theme analysis
- **Storage**: Browser-based (IndexedDB for demo)

## Production Architecture
For 1,000+ transcripts:
```
Voice/Data Input → Batch Ingestion → ETL Pipeline
                          ↓
                   PostgreSQL + Vector DB
                          ↓
                  Background Processing
                          ↓
                   LLM Analysis (Claude)
                          ↓
                   Dashboard Output
```

## Built With
- Vanilla JavaScript (no dependencies)
- Claude API for AI analysis
- TF-IDF + K-means (custom implementation)

---

**Note**: This is a functional prototype demonstrating transcript analysis capabilities for educational research workflows.