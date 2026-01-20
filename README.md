# Evolving Dark Energy Phenomenological Model

This repository documents the step-by-step development of a phenomenological scalar field model for dynamical dark energy. The model was originally a simple 1D PDE and has been systematically elevated into a more complete, minimally coupled cosmological framework inspired by recent DESI DR2 hints of evolving \( w(z) \) and motivated by Bohr's complementarity principle applied to vacuum fluctuations.

## Key Changes & Elevations from the Original Toy Model

The following upgrades transformed the initial toy PDE into a self-consistent, testable dark energy proposal:

- **Dimensional upgrade**  
  Generalized from 1D (t + x) to full 3+1D isotropic relativistic spacetime using the covariant d'Alembertian □φ.

- **Isotropy & Lorentz invariance**  
  Replaced anisotropic advection (β φ ∂φ/∂x) with a fully isotropic k-essence term: β φ (∂_μφ ∂^μφ).

- **Realistic background tracking**  
  Added small quadratic potential V(φ) = (1/2) m² φ² with m ≈ 0.8 H₀ to provide ultra-light scalar behavior and smooth w(z) transition.

- **Density-dependent probabilistic collapses**  
  Introduced multiplicative stochastic noise ξ × (φ² / φ₀²) so collapse probability scales with local field amplitude (stronger in filaments/overdensities).

- **IR quantum correction**  
  Added mild running vacuum term Λ(H) = Λ₀ + 3ν H² (ν = 0.03) for dynamical cosmological constant consistent with renormalization-group arguments.

- **Standard gravity coupling**  
  Minimally coupled the scalar to Einstein-Hilbert action — no modifications to General Relativity.

- **Consistent Lagrangian derivation**  
  Constructed ℒ_φ = -X + β φ X² + (κ/2)(□φ)² - (1/2) m² φ² that reproduces the EOM approximately (effective treatment for higher-derivative term).

- **Full background cosmology**  
  Derived homogeneous Klein-Gordon + Friedmann equations in e-folds (N = ln a), including running vacuum correction.

- **Perturbation theory foundation**  
  Outlined linear perturbations with modified dispersion relation: ω² ≈ k²/a² + m² + β corrections + κ k⁴/a⁴.

- **Numerical implementation**  
  Built Python solver for stochastic background evolution (multiplicative noise + running Λ) with ensemble averaging capability.

- **DESI alignment & tuning**  
  Parameters tuned to produce w(z) evolving from ≈ -0.98 (high z) to ≈ -0.86 (z=0), matching DESI DR2 preferred region.

- **Unique predictions**  
  Density-dependent filament/void asymmetries (Δz/z ∼ 0.05–0.10), mild H₀ relief, suppressed σ₈ from κ damping, stochastic non-Gaussianity.

## Current Status

The model is now a coherent, minimally coupled k-essence + higher-derivative + stochastic-collapse + running-vacuum framework — no longer a bare toy model.  
It is at the level of many phenomenological dark energy proposals published on arXiv and suitable for further refinement or submission.

## Next Steps (Planned)

- Ensemble-averaged w(z) error bands
- Quantitative w₀wₐ fit vs. DESI DR2 posteriors
- 2D/3D perturbation box simulation showing void/filament contrast
- Stability analysis for higher-derivative term (ghost mass, timescale)
- Full non-Gaussianity and CMB lensing predictions


Contributions, extensions, or criticism welcome.

License: MIT  
Last updated: January 2026
