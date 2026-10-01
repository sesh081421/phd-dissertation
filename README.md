# Ph.D. Dissertation Website

This repository hosts the GitHub Pages website for:

**Representation Learning for Biological Inference from Single-Cell Transcriptomics**

Sanghun Sel  
Advisor: Giltae Song  
Division of AI, Pusan National University  
Ph.D. Dissertation, February 2027

## GitHub Pages

Repository name:

```text
phd-dissertation
```

Expected URL:

```text
https://sesh081421.github.io/phd-dissertation/
```

## How to publish

1. Create or open the GitHub repository `phd-dissertation`.
2. Upload `index.html`, `style.css`, and the `assets` folder to the repository root.
3. Open **Settings → Pages**.
4. Under **Build and deployment**, choose **Deploy from a branch**.
5. Select:
   - Branch: `main`
   - Folder: `/ (root)`
6. Save.

The page should then be available at:

```text
https://sesh081421.github.io/phd-dissertation/
```

## Files to replace before final submission

### Dissertation PDF

Place the final dissertation PDF here:

```text
assets/files/dissertation.pdf
```

### Links in index.html

Replace placeholder `href="#"` links for:

- scTrans-SVD paper
- scTrans-SVD source code
- ReSPAR source code
- Testing data
- Demonstration video

### References

Update the selected references with final publication metadata and DOI information.

### Results

Replace the general Results and Performance descriptions with final dissertation results and numerical values once all experiments are finalized.

## Suggested additions

If desired, add dissertation figures to:

```text
assets/figures/
```

Recommended figures:

- dissertation overview figure
- scTrans-SVD framework
- TRACE framework
- ReSPAR framework
- selected results figure

Keep the site simple and static to match the departmental requirement for a clear, non-complex dissertation introduction website.


## Naming convention

The public-facing dissertation website uses research-topic titles rather than individual model names.
Model names may be retained only inside publication metadata or repository URLs when necessary.
