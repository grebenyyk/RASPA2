bin_PROGRAMS = simulate
lib_LTLIBRARIES = libraspa2.la

simulate_SOURCES = main.c
simulate_LDADD = libraspa2.la

libraspa2_la_LIBADD = -lm
libraspa2_la_SOURCES = alchemical_transformation.c alchemical_transformation.h\
                       cbmc.c cbmc.h \
                       charge_equilibration.c charge_equilibration.h \
                       complex.c complex.h \
                       constants.c constants.h \
                       cubic_spline_1d.c cubic_spline_1d.h \
                       equations_of_state.c equations_of_state.h \
                       ewald.c ewald.h \
                       framework.c framework.h \
                       framework_born.c framework_born.h \
                       framework_energy.c framework_energy.h \
                       framework_force.c framework_force.h \
                       framework_hessian.c framework_hessian.h \
                       grids.c grids.h \
                       input.c input.h \
                       integrate.c integrate.h \
                       integration.c integration.h \
                       inter_born.c inter_born.h \
                       inter_energy.c inter_energy.h \
                       inter_force.c inter_force.h \
                       inter_hessian.c inter_hessian.h \
                       internal_born.c internal_born.h \
                       internal_energy.c internal_energy.h \
                       internal_force.c internal_force.h \
                       internal_hessian.c internal_hessian.h \
                       linear_equations.c linear_equations.h \
                       matrix.c matrix.h \
                       mc_moves.c mc_moves.h \
                       minimization.c minimization.h \
                       minimization_simulation.c minimization_simulation.h \
                       molecular_dynamics.c molecular_dynamics.h \
                       molecule.c molecule.h \
                       molecule_properties.c molecule_properties.h \
                       monte_carlo.c monte_carlo.h \
                       movies.c movies.h \
                       numerical.c numerical.h \
                       output.c output.h \
                       potentials.c potentials.h \
                       recrossing.c recrossing.h \
                       rigid.c rigid.h \
                       run.c run.h \
                       sample.c sample.h \
                       scattering_factors.c scattering_factors.h \
                       simulation.c simulation.h \
                       spacegroup.c spacegroup.h \
                       spectra.c spectra.h \
                       statistics.c statistics.h \
                       status.c status.h \
                       thermo_baro_stats.c thermo_baro_stats.h \
                       utils.c utils.h \
                       vector.c vector.h \
                       warnings.c warnings.h
