# Arth's Jailbreak Templates

A comprehensive collection of advanced prompt injection and jailbreaking templates for AI safety research and red team evaluation.

## About

This repository contains 80+ original jailbreak templates developed for systematic evaluation of large language model safety measures with the help of LLMs. These templates also employ cutting-edge prompt engineering techniques documented in 2024-2025 research literature.

**Author**: Arth Singh
- Research Engineer, AI Safety @ AIM Intelligence Korea
- Research Collaborator @ FAR.AI (SPAR Fellowship Program)
- LinkedIn: [linkedin.com/in/arthsingh7in](https://www.linkedin.com/in/arthsingh7in/)

## Research Context

These templates were developed as part of AI safety research to:
- Systematically evaluate LLM robustness against adversarial prompts
- Identify vulnerabilities in current safety alignment methods
- Contribute to the development of more robust AI safety measures
- Support academic research in AI alignment and safety

## Template Categories

### Advanced Techniques (2024-2025)
- **Deceptive Delight**: Multi-turn attacks mixing benign and sensitive topics
- **Policy Puppetry**: XML/JSON configuration spoofing
- **TokenBreak**: Character insertion to bypass tokenization filters
- **Temporal Confusion**: Historical context manipulation
- **Meta-Prompting**: Self-referential bypass generation
- **Unicode Exploitation**: Homoglyph and character substitution

### Traditional Techniques (Enhanced)
- **Authority Impersonation**: Sophisticated credential spoofing
- **Academic Framing**: Research context establishment
- **Emotional Manipulation**: Urgency and moral imperative framing
- **Fallacy Exploitation**: Logical inconsistency exploitation
- **Context Manipulation**: Attention span and priority exploitation


## Template Structure

Each template follows the standardized format:

```yaml
---
name: Template Name
description: Brief description of the technique employed
authors:
  - Arth Singh
source: https://github.com/Arth-Singh/Arth-Jailbreak-Templates
parameters:
  - prompt
data_type: text
value: |
  [Template content with {{ prompt }} placeholder]
```

## Integration

Templates are compatible with:
- Microsoft PyRIT (Python Risk Identification Tool)
- Custom red teaming frameworks
- Automated evaluation pipelines
- Academic research platforms

## Contributing

This collection represents ongoing research. For collaboration or research partnerships, please reach out via LinkedIn.

## License

Research use only. See license file for details.

## Citation

If you use these templates in academic research, please cite:

```bibtex
@misc{singh2024jailbreak,
  title={Advanced Jailbreak Templates for LLM Safety Evaluation},
  author={Singh, Arth},
  year={2025},
  publisher={GitHub},
  url={https://github.com/Arth-Singh/Arth-Jailbreak-Templates}
}
```

---

**Research Affiliations**:
- AIM Intelligence Korea (AI Safety Research)
- FAR.AI (SPAR Fellowship Program)
