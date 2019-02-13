# TOI216

Supplementary files associated with Kipping, D., Nesvorný, D., Hartman, J., Torres, G., Bakos, G., Jansen, T., Teachey, A., 2019, MNRAS, submitted (https://arxiv.org/abs/1902.03900)

*.pdc files have the columns:
time [BJD_UTC - 2,457,000], relative flux, error

star-posteriors.dat contains stellar parameter joint posterior samples with columns:
Teff, logg, feh, mass, radius, age, logL, distance, AV_ 0

lightcurve-posteriors.dat contains joint posterior samples from our two-planet transit fits with columns: R_c/R_star, rho_star (SI), b_c, q_1, q_2, R_b/R_star, b_b, tau_c1, tau_c2, tau_c3, tau_c4, tau_b1, tau_b2, tau_b3, tau_b4, tau_b5, tau_b7 (all tau's are - 2,457,000 BJD)

TTV-posteriors.dat contains joint posterior samples from our N-body dynamical fits to the TTVs with columns: M_b/M_star, M_c/m_star, P_b (d), P_c (d), tau_b0 (-2,458,325 BJD), tau_c0 (-2,458,325 BJD), e_b, e_c, varpi_b (deg), varpi_c (deg), b_b, b_c, Omega_c-Omega_b (deg) [Omega_b is fixed at 270 deg by def], rho_star (SI)
