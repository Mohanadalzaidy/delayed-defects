arXiv submission notes
======================

This archive contains the LaTeX source for:

  "Delay-Induced Synchronization and Defect-Mediated Dynamics in an
   Oscillatory FitzHugh-Nagumo Lattice"

Compilation
-----------
  pdflatex main.tex
  pdflatex main.tex      (second pass resolves the inline bibliography)

The source is self-contained:
  - bibliography is inline (thebibliography environment; no .bib file),
  - no \includegraphics (all results in tables/text),
  - no \input or \include dependencies,
  - standard packages only (amsmath, graphicx, booktabs, siunitx,
    hyperref, etc.).

Scope
-----
This is a computational nonlinear-dynamics study. It is not a cardiac,
medical, governance, or predictive-control model. See the Scope
Declaration and Disclaimer near the end of the paper.

Associated code
---------------
The full reproducibility code (simulation engine, defect tracking, ECPI,
tests, provenance) is released separately as the "delayed-defects"
repository, tag v1.0.0-arxiv, with canonical hash f2de5afe1fd5da01.
