In order to build the DQMH libraries into a PPL, drag them into the DQMH PPL.lvlib in the project and then build the DQMH PPL build specification.

You will need to replace in all your DQMH modules to use the DQMH PPL instead of the DQMH libraries.

When you are done, remember to remove the DQMH libraries from the DQMH PPL.lvlib. 

If you were using DQMH 5.0 or later, you could create a DQMH Module Template that calls the functions from the PPL and the scripting tools would still work. You would only need to specify to use the DQMH enqueue function from the PPL when creating new events.