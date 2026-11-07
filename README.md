# CV

| Folder | Use for | Pages |
|---|---|---|
| `academic/general/` | Default PhD/research CV (embedded + HPC) | 4 |
| `academic/hpc/` | HPC, compilers, SYCL, GPU positions | 4 |
| `academic/embedded-fpga/` | Embedded, FPGA, hardware design positions | 4 |
| `academic-with-transcript/` | The three academic CVs above plus the Academic Transcript page, for applications that ask for it. **Private: in .gitignore, never pushed.** Small wrapper files: edit the CV text in `academic/`, the grades in `academic-with-transcript/transcript.tex`. | 5 |
| `industry/hpc/` | Industry: HPC & performance software engineer | 2 |
| `industry/embedded/` | Industry: embedded systems engineer | 2 |
| `archive/` | Older versions, kept for reference only | |

Build:

```bash
pdflatex MohammadVazirpanah-CV.tex   # run twice; output: MohammadVazirpanah-CV.pdf
```

Official transcripts are the stamped Najit translations in `../degrees/Najit/`.
