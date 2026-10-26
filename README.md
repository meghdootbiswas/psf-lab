# PSF Lab: Point Spread Function & Airy Disk Simulator

**Live site: https://meghdootbiswas.github.io/psf-lab/**

An interactive, browser-based simulator of the **point spread function (PSF)**, the **Airy disk and Airy pattern**, the **Rayleigh criterion** and the **diffraction limit** of optical resolution, with applications from light microscopy and CD/DVD/Blu-ray readers to **DUV and EUV photolithography**.

## What you can do

- **PSF explorer:** change the wavelength and F-number and watch the Airy disk grow and shrink at a fixed scale; read off the Airy radius r = 0.61 λ/NA, the FWHM and the depth of focus λ/NA².
- **Rayleigh criterion:** move two point sources together and see when they stop being resolvable (Rayleigh 0.61 λ/NA, Sparrow 0.47 λ/NA).
- **Lithography resolution:** compute the aerial image of a line/space mask under dipole illumination, and see why CD = k₁ λ/NA stops at k₁ = 0.25 for g-line, i-line, KrF, ArF, ArF immersion, EUV and High-NA EUV scanners.
- **Optical discs:** compare the laser spots of CD (780 nm), DVD (650 nm) and Blu-ray (405 nm) against their track pitch.

## How it is computed

The PSF is the Airy pattern [2J₁(v)/v]² with v = 2π·NA·r/λ for an aberration-free circular pupil, with NA = 1/(2·F/#). Line images sum the mask diffraction orders that pass the pupil. All sources are cited on the page.

## Files

| File | Purpose |
|---|---|
| `index.html` | The whole site: one self-contained page, no build step |
| `preview.png` | 1200×630 image shown when the link is shared |
| `sitemap.xml` | Submitted to Google Search Console |

## Author

Meghdoot Biswas, PhD student, LOFT Group, Wyant College of Optical Sciences, The University of Arizona. meghdoot@arizona.edu · [LinkedIn](https://www.linkedin.com/in/meghdootbiswas/)
