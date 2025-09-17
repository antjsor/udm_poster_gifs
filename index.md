# Simulation Results

## Animations for results show on the poster.
### Video for 15 AR-Step network for event 55313
![Results for 15 AR-Step network for event 55313](sim_movie_55313_dif_55313.gif) 
### Video for 15 AR-Step network for event 68370
![Results for 15 AR-Step network for event 68370](sim_movie_68370_dif_68370.gif)
### Video for 15 AR-Step network for event 69313
![Results for 15 AR-Step network for event 69313](sim_movie_69313_dif_69313.gif)


## Results for testing on larger domain, for network trained without absolute terrain height as feature.
For these results we chose the best performing network out of a batch of 4, as measured by the validation loss, and mass balance.
We use the three rain events, 55313, 68370 and 69313 from the presentation, and create 3 new 256x256 terrain rasters. However unlike the presentation, the network is evalauted on all 9 rain/terrain combinations. All the networks here we trained using 15 AR-steps since that seemed to be a good value.

## Balance plots
We that the mass balances are not as well conserved for the larger domain, and the surrogates face have larger problems especially for terrain 3.
![Results_mass_balance](all_vol_with_rain.svg)


## Videos of simualtions
### Video for 15 AR-Step network for event 55313 on terrain 1
Something seems to have gone for this specific rain/terrain combinations such that MIKE does not aggregate water at local peaks.
![Results 55313 ter1](sim_movie_55313_ter1.gif) 
### Video for 15 AR-Step network for event 55313 on terrain 2
![Results 55313 ter2](sim_movie_55313_ter2.gif) 
### Video for 15 AR-Step network for event 55313 on terrain 3
![Results 55313 ter1](sim_movie_55313_ter3.gif) 


### Video for 15 AR-Step network for event 68370 on terrain 1
![Results 68370 ter1](sim_movie_68370_ter1.gif) 
### Video for 15 AR-Step network for event 68370 on terrain 2
![Results 68370 ter2](sim_movie_68370_ter2.gif) 
### Video for 15 AR-Step network for event 68370 on terrain 3
![Results 68370 ter1](sim_movie_68370_ter3.gif) 


### Video for 15 AR-Step network for event 69313 on terrain 1
![Results 69313 ter1](sim_movie_69313_ter1.gif) 
### Video for 15 AR-Step network for event 69313 on terrain 2
![Results 69313 ter2](sim_movie_69313_ter2.gif) 
### Video for 15 AR-Step network for event 69313 on terrain 3
![Results 69313 ter1](sim_movie_69313_ter3.gif) 


