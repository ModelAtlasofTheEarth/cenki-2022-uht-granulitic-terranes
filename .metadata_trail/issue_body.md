### -> submitter ORCID (or name)

https://orcid.org/0000-0001-7649-4498

### -> slug

cenki-2022-uht-granulitic-terranes

### -> license

CC-BY-4.0

### -> alternative license URL

_No response_

### -> model category

model published in study

### -> model status

completed

### -> associated publication DOI

https://doi.org/10.1111/ter.12577

### -> model creators

0000-0001-7649-4498
0000-0002-1767-8593
0000-0001-6773-0807
0000-0003-4515-9296

### -> title

_No response_

### -> description

Long-lived high to ultra-high temperature (HT-UHT) granulitic terranes formed throughout Earth's history. Yet, the detailed processes involved in their formation remain unresolved and notably the sequence of appearance and duration of migmatisation and granulites conditions in the orogenic cycle. These processes can be evaluated by analytical and numerical models. First, solving the steady-state heat equation allows underlining the interdependency of the parameters controlling the crustal geotherm at thermal equilibrium. Second, performing two-dimensional thermo-mechanical experiments of an orogenic cycle, from shortening to gravitational collapse, allows to consider non-steady-state geotherms and understand how deformation velocity may affect the relative timing of migmatite and granulite formation. These numerical experiments with elevated radiogenic heat production and slow shortening rates allow the formation of large volumes of prograde migmatites and granulites going through the sillimanite field as observed in many HT-UHT terranes. Finally, the interplay between these parameters can explain the difference in predicted pressure-temperature-time paths that can be compared with the natural rock archive.

### -> abstract

_No response_

### -> scientific keywords

_No response_

### -> funder

European Union's Horizon 2020 research and innovation program under grant agreement no 793978

### -> model embargo?

_No response_

### -> include model code ?

- [X] yes

### -> model code/inputs DOI

https://github.com/underworld-community/cenki-et-al-UHT-granulitic-terranes

### -> model code/inputs notes

_No response_

### -> include model output data?

- [X] yes

### -> data creators

_No response_

### -> model output data DOI

_No response_

### -> model output data notes

_No response_

### -> model output data size

_No response_

### -> software framework DOI/URI

https://doi.org/10.5281/zenodo.3975252

### -> software framework source repository

_No response_

### -> name of primary software framework (e.g. Underworld, ASPECT, Badlands, OpenFOAM)

Underworld 2

### -> software framework authors

_No response_

### -> software & algorithm keywords

Python, Finite Element

### -> computer URI/DOI

_No response_

### -> add landing page image and caption

[Figure2_v9.pdf](https://github.com/user-attachments/files/16707129/Figure2_v9.pdf)

Figure 2. A-B. Model geometry, initial conditions as well as geotherm, viscosity and density profiles. The circles pattern superimposed on the continental crust represents the finite strain ellipses. White squares represent the Lagrangian particles recording the PTt paths presented in Fig. 4. A. Initial conditions for models RHP2_diff, mimicking a Proterozoic highly differentiated and highly radiogenic crust. B. Initial conditions for model RHP1_unif, simulating a Phanerozoic uniform and less radiogenic crust. C-J. Orogenic modeling results showing two snapshots for each model: i) shortening-delamination and ii) collapse. Shortening velocity is either slow (0.24 cm.y-1, C-F) or fast (2.4 cm.y-1, G-J). 

### -> add an animation (if relevant)

_No response_

### -> add a graphic abstract figure (if relevant)

[Figure3_v6.pdf](https://github.com/user-attachments/files/16707137/Figure3_v6.pdf)

Figure 3. Depth – time profiles indicating the onset of partial melting and granulite formation through the evolution of the models. 

### -> add a model setup figure (if relevant)

_No response_

### -> add a description of your model setup

The numerical models are performed with Underworld, a well-tested open-source finite element code, to solve the equations of conservation of momentum, mass, and energy for an incompressible fluid on a Cartesian Eulerian mesh (Moresi et al., 2007; Beucher et al., 2019). The 2D thermo-mechanical experiments involve a geological model of dimensions 480 km x 160 km discretized over a computational grid made of 240 x 80 elements. The initial setup consists of a 35 km or 40 km thick crust with 20 km of air-like material above, and mantle below (Fig. 2A-B). Each model runs through three stages: 

i) a shortening phase during which the crust thickens to ~ 60 km with either a slow total velocity of 0.24 cm/yr during 70 My or a fast total velocity of 2.4 cm/yr during ~ 7 My (delivering a strain rate averaged over the length of the model of $1.6 \times 10^{-16} s^{-1}$ and $1.6 \times 10^{-15} s^{-1}$ respectively); ii) a rapid increase in BHF (from $0.020 W/m^2$ to $0.030 W/m^2$) over 2.5 My while the velocities imposed on the vertical boundaries are set to zero (vx = vy = 0 cm/yr) mimicking the thermal impact of a mantle delamination phase; iii) a relaxation phase in which the crust returns to normal thickness under slow extensional boundary conditions (total velocity of 0.10 cm/yr) associated with a decrease in BHF from $0.030 W/m^2$ to $0.020 W/m^2$ in ~ 70 My. Details of modeling procedures, rheological and thermal parameters, as well as the input Python script, are available as supplementary data.

These experiments focus on two end-member crustal structures with average values of total RHP at ~ $1 \mu W/m^3$ and ~ $2 \mu W/m^3$ (Fig. 2). A value of ~ $1 \mu W/m^3$ is in line with RHP calculations predicted from the present-day composition of the bulk continental crust determined by Taylor and McLennan (1995). Models RHP1_unif mimic a Phanerozoic orogenic cycle involving a continental crust with a uniform RHP ($1.0483 \mu W/m^3$) yielding an initial Moho temperature of 650°C at 40 km depth (Fig. 1A). However, Mareschal and Jaupart (2013), Artemieva et al. (2017), and Gard et al. (2019) showed that the crustal RHP may have been higher than ~ $1 \mu W/m^3$ during the Proterozoic, having varied between ~ $0.8 \mu W/m^3$ and ~ $4 \mu W/m^3$ between 0.5 Ga and 2.5 Ga with an average RHP close to ~ $2 \mu W/m^3$. In addition, recent studies reveal that, in tectonically stable regions, the upper crust’s RHP may be higher than in the lower crust (Goes et al., 2020; Alessio et al., 2020). The conditions for model RHP2_diff include a total average RHP of ~ $2.0922 \mu W/m^3$ with high RHP in the upper crust (~ $5 \mu W/m^3$) that decreases exponentially with a length scale factor $h_c$ of 20 km yielding an initial Moho temperature at 35 km depth of 650°C (Fig. 1D). Models RHP2_diff aim at approaching thermal conditions of a differentiated crust prevailing during the Proterozoic.

### Please provide any feedback on the model submission process?

_No response_