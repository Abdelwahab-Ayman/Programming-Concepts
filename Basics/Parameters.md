##### Parameters is special kind of variable used in subroutines to refer to one of the pieces of data provided as input to the subroutines.
>Parameters : is a variable which is part of methods signature .<br>
as Parameters = variables

#### Parameter : is a special kind of variables used in function  

```mermaid
classDiagram
    Parameters <|-- Variables
    Parameters <|-- Argument
    Parameters : +used in functions to refer to one of the pieces of the data.
    Parameters : +Provided as an input to the functions
    Parameters : +Arguments are assigned to Parameters ()

    class Variables{
      +This pieces of data are the value of the argument
      +which is going to be called or invoked
      +Each Arguments is Parameters but not each parameter is argument()
    }
    class Argument{
      -each time the function is called ,it`s argument is evaluated
      -and the resultinf value is assigned to the corresponding parameters
            +Arguments and paremeters are interferneced concepts()

    }

```
![Argument vs parameters](https://github.com/Abdelwahab-Ayman/Programming-Concepts/blob/main/Basics/Arguments%20Vs%20Parameters.png)

