400 Lennard-Jones particles run for 10,000 steps.

To run:
gmx grompp -c lj_bulk.gro -f lj_bulk.mdp -p lj_bulk.top -o lj_bulk.tpr
gmx mdrun -s lj_bulk.tpr -c lj_bulk_output.gro -e lj_bulk.edr -o lj_bulk.trr -g lj_bulk.log

Produces:
	intermediate file:
		     lj_bulk.tpr
        output file:
		lj_bulk_output.gro
		lj_bulk.edr
		lj_bulk.trr
		lj_bulk.log
