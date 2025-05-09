# AI 2027 Timelines and Takeoff Simulations

This is the code to run the simulations for AI 2027's [timelines forecast](https://ai-2027.com/research/timelines-forecast) and [takeoff forecast](https://ai-2027.com/research/takeoff-forecast).

Use `poetry install` to install needed packages.

To run the timelines simulation, input your parameters in the `simulation/params.yaml` file. 

Then, cd into the `timelines` folder and run `poetry run python forecasting_timelines.py` to run the benchmarks and gaps method. Run `simple_forecasting_timelines.py` to run the time horizon extensionmethod. The results are saved in the `figures` folder.

To run the takeoff simulation, input your parameters in `takeoff/params.yaml`, cd into `takeoff` then run `forecasting_takeoff.py`.

We'd love for others run the simulations with their own parameters or extend our work. For example, due to time constraints we weren't able to incorporate training compute increases or uncertainty over AI R&D progress multipliers in our takeoff simulation.

The simulation was implemented by Nikola Jurkovic and Eli Lifland.