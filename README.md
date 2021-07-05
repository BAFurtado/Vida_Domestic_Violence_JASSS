# VIDA: A simulation model of domestic VIolence in times of social DistAncing

### Lígia Mori Madeira ¹ ³ 

### Bernardo Alves Furtado ² ³ 

### Alan Rafael Dill ¹ ³

¹ Department of Political Science at Federal University of Rio Grande do Sul (UFRGS)

² Institute for Applied Economic Research (Ipea)

³ National Council for Technological Development (CNPq)

Corresponding author: bernardo.furtado@ipea.gov.br

Accepted for publication at JASSS

A permanent version of the code is also available at ComSES: 
https://www.comses.net/codebases/ade80a69-82fa-4258-88ae-d17fb7094e23/releases/1.0.2/ 

## To run the model

1. Fork and `git clone` the model
2. Install mesa: `pip install mesa`
3. To run a test of policy, simply run `python generalization.py`. You may alter the number of iterations or output folder.
A CSV file is saved in default `'output'` folder
   
4. Changing the default metropolis of Brasília is also possible, altering the name of the metropolis on line 47 or 48 
   of file `generalization_aps.py` and then running `python generalization_aps.py`
   
5. An early visual demonstration is also possible to set in your browser, running `mesa runserver`
6. Some plots are available at `plotting.py`

