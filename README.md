# unifyHE

![Work In Progress](https://img.shields.io/badge/Status-Work%20In%20Progress-red)
> This package is currently a prototype. Contributions and integration with wider HTA standards are welcome.

A health economics modelling meta-language.

Example high-level workflow code

```r
he_workflow <- workflow() %>%
  add_model(stat_mod) %>%
  set_scenarios(init_pop = c(init_prop04, init_prop06)) %>% 
  add_simulation(model = economic_mod, params = sim_params) %>%
  cea()  # cost-effectiveness analysis
```

See [documentation]()
