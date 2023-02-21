# useState
## The useState hook is a special 
## function that takes the initial 
## state as an argument and 
## returns an array of two entries

# Sytanxsis 
import {UseState} from 'React'

How To Use

const [date,setDate] = useState("1991")

date = IS Variable 
setDate = IS the Function That change our Variable

# UseEffect
## React useEffect is a function that gets executed for 3 
## different React component lifecycles.
## Those lifecycles are componentDidMount, 
## componentDidUpdate, and componentWillUnmount 
## lifecycles.


UseEffect Is Kneed to refresh What we want to do

# Sytanxsis 
import {UseEffect} from 'React'

How To Use

useEffect(()=>{},[])


# Rules to Remember
## Don’t call Hooks inside 
## loops, conditions, or nested 
## functions. Instead, always 
## use Hooks at the top level of 
## your React function, before 
## any early returns