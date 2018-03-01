# Assembly <code>Monacs.Core</code>

## Type <a name="T%3aMonacs.Core.Async.Result"><code>Monacs.Core.Async.Result</code></a>
 Contains the set of async extensions to work with the [<c>Result\`1</c>](#T%3aMonacs.Core.Result%601) type.


### Methods
#### Method <a name="M%3aMonacs.Core.Async.Result.BindAsync%60%602(Monacs.Core.Result%7b%60%600%7d%2cSystem.Func%7b%60%600%2cSystem.Threading.Tasks.Task%7bMonacs.Core.Result%7b%60%601%7d%7d%7d)"><code>BindAsync</code></a>
 Transforms the [<c>result</c>](#result) into another [<c>Result\`1</c>](#T%3aMonacs.Core.Result%601) using the [<c>binder</c>](#binder) function.             If the input result is Ok, returns the value of the binder call (which is [<c>Result\`1</c>](#T%3aMonacs.Core.Result%601) of [<c>TOut</c>](#TOut) ).             Otherwise returns Error case of the Result of [<c>TOut</c>](#TOut) .






##### Generic parameters
|Name|Description|
|---|---|
|TIn|Type of the value in the input result.|
|TOut|Type of the value in the returned result.|

##### Parameters
|Name|Description|
|---|---|
|result|The result to bind with.|
|binder|Function called with the input result value if it's Ok case.|

#### Method <a name="M%3aMonacs.Core.Async.Result.BindAsync%60%602(System.Threading.Tasks.Task%7bMonacs.Core.Result%7b%60%600%7d%7d%2cSystem.Func%7b%60%600%2cSystem.Threading.Tasks.Task%7bMonacs.Core.Result%7b%60%601%7d%7d%7d)"><code>BindAsync</code></a>
 Transforms the [<c>result</c>](#result) into another [<c>Result\`1</c>](#T%3aMonacs.Core.Result%601) using the [<c>binder</c>](#binder) function.             If the input result is Ok, returns the value of the binder call (which is [<c>Result\`1</c>](#T%3aMonacs.Core.Result%601) of [<c>TOut</c>](#TOut) ).             Otherwise returns Error case of the Result of [<c>TOut</c>](#TOut) .






##### Generic parameters
|Name|Description|
|---|---|
|TIn|Type of the value in the input result.|
|TOut|Type of the value in the returned result.|

##### Parameters
|Name|Description|
|---|---|
|result|The result to bind with.|
|binder|Function called with the input result value if it's Ok case.|

#### Method <a name="M%3aMonacs.Core.Async.Result.BindAsync%60%602(System.Threading.Tasks.Task%7bMonacs.Core.Result%7b%60%600%7d%7d%2cSystem.Func%7b%60%600%2cMonacs.Core.Result%7b%60%601%7d%7d)"><code>BindAsync</code></a>
 Transforms the [<c>result</c>](#result) into another [<c>Result\`1</c>](#T%3aMonacs.Core.Result%601) using the [<c>binder</c>](#binder) function.             If the input result is Ok, returns the value of the binder call (which is [<c>Result\`1</c>](#T%3aMonacs.Core.Result%601) of [<c>TOut</c>](#TOut) ).             Otherwise returns Error case of the Result of [<c>TOut</c>](#TOut) .






##### Generic parameters
|Name|Description|
|---|---|
|TIn|Type of the value in the input result.|
|TOut|Type of the value in the returned result.|

##### Parameters
|Name|Description|
|---|---|
|result|The result to bind with.|
|binder|Function called with the input result value if it's Ok case.|

#### Method <a name="M%3aMonacs.Core.Async.Result.MapAsync%60%602(Monacs.Core.Result%7b%60%600%7d%2cSystem.Func%7b%60%600%2cSystem.Threading.Tasks.Task%7b%60%601%7d%7d)"><code>MapAsync</code></a>
 Maps the value of the [<c>result</c>](#result) into another [<c>Result\`1</c>](#T%3aMonacs.Core.Result%601) using the [<c>mapper</c>](#mapper) function.             If the input result is Ok, returns the Ok case with the value of the mapper call (which is [<c>TOut</c>](#TOut) ).             Otherwise returns Error case of the Result of [<c>TOut</c>](#TOut) .






##### Generic parameters
|Name|Description|
|---|---|
|TIn|Type of the value in the input result.|
|TOut|Type of the value in the returned result.|

##### Parameters
|Name|Description|
|---|---|
|result|The result to map on.|
|mapper|Function called with the input result value if it's Ok case.|

#### Method <a name="M%3aMonacs.Core.Async.Result.MapAsync%60%602(System.Threading.Tasks.Task%7bMonacs.Core.Result%7b%60%600%7d%7d%2cSystem.Func%7b%60%600%2cSystem.Threading.Tasks.Task%7b%60%601%7d%7d)"><code>MapAsync</code></a>
 Maps the value of the [<c>result</c>](#result) into another [<c>Result\`1</c>](#T%3aMonacs.Core.Result%601) using the [<c>mapper</c>](#mapper) function.             If the input result is Ok, returns the Ok case with the value of the mapper call (which is [<c>TOut</c>](#TOut) ).             Otherwise returns Error case of the Result of [<c>TOut</c>](#TOut) .






##### Generic parameters
|Name|Description|
|---|---|
|TIn|Type of the value in the input result.|
|TOut|Type of the value in the returned result.|

##### Parameters
|Name|Description|
|---|---|
|result|The result to map on.|
|mapper|Function called with the input result value if it's Ok case.|

#### Method <a name="M%3aMonacs.Core.Async.Result.MapAsync%60%602(System.Threading.Tasks.Task%7bMonacs.Core.Result%7b%60%600%7d%7d%2cSystem.Func%7b%60%600%2c%60%601%7d)"><code>MapAsync</code></a>
 Maps the value of the [<c>result</c>](#result) into another [<c>Result\`1</c>](#T%3aMonacs.Core.Result%601) using the [<c>mapper</c>](#mapper) function.             If the input result is Ok, returns the Ok case with the value of the mapper call (which is [<c>TOut</c>](#TOut) ).             Otherwise returns Error case of the Result of [<c>TOut</c>](#TOut) .






##### Generic parameters
|Name|Description|
|---|---|
|TIn|Type of the value in the input result.|
|TOut|Type of the value in the returned result.|

##### Parameters
|Name|Description|
|---|---|
|result|The result to map on.|
|mapper|Function called with the input result value if it's Ok case.|

#### Method <a name="M%3aMonacs.Core.Async.Result.MatchAsync%60%602(Monacs.Core.Result%7b%60%600%7d%2cSystem.Func%7b%60%600%2cSystem.Threading.Tasks.Task%7b%60%601%7d%7d%2cSystem.Func%7bMonacs.Core.ErrorDetails%2cSystem.Threading.Tasks.Task%7b%60%601%7d%7d)"><code>MatchAsync</code></a>
 Does the pattern matching on the [<c>Result\`1</c>](#T%3aMonacs.Core.Result%601) type.             If the [<c>result</c>](#result) is Ok, calls [<c>ok</c>](#ok) function             with the value from the result as a parameter and returns its result.             Otherwise calls [<c>error</c>](#error) function and returns its result.







##### Generic parameters
|Name|Description|
|---|---|
|TIn|Type of the value in the result.|
|TOut|Type of the returned value.|

##### Parameters
|Name|Description|
|---|---|
|result|The result to match on.|
|ok|Function called for the Ok case.|
|error|Function called for the Error case.|

#### Method <a name="M%3aMonacs.Core.Async.Result.MatchAsync%60%602(Monacs.Core.Result%7b%60%600%7d%2cSystem.Func%7b%60%600%2cSystem.Threading.Tasks.Task%7b%60%601%7d%7d%2cSystem.Func%7bMonacs.Core.ErrorDetails%2c%60%601%7d)"><code>MatchAsync</code></a>
 Does the pattern matching on the [<c>Result\`1</c>](#T%3aMonacs.Core.Result%601) type.             If the [<c>result</c>](#result) is Ok, calls [<c>ok</c>](#ok) function             with the value from the result as a parameter and returns its result.             Otherwise calls [<c>error</c>](#error) function and returns its result.







##### Generic parameters
|Name|Description|
|---|---|
|TIn|Type of the value in the result.|
|TOut|Type of the returned value.|

##### Parameters
|Name|Description|
|---|---|
|result|The result to match on.|
|ok|Function called for the Ok case.|
|error|Function called for the Error case.|

#### Method <a name="M%3aMonacs.Core.Async.Result.MatchAsync%60%602(Monacs.Core.Result%7b%60%600%7d%2cSystem.Func%7b%60%600%2c%60%601%7d%2cSystem.Func%7bMonacs.Core.ErrorDetails%2cSystem.Threading.Tasks.Task%7b%60%601%7d%7d)"><code>MatchAsync</code></a>
 Does the pattern matching on the [<c>Result\`1</c>](#T%3aMonacs.Core.Result%601) type.             If the [<c>result</c>](#result) is Ok, calls [<c>ok</c>](#ok) function             with the value from the result as a parameter and returns its result.             Otherwise calls [<c>error</c>](#error) function and returns its result.







##### Generic parameters
|Name|Description|
|---|---|
|TIn|Type of the value in the result.|
|TOut|Type of the returned value.|

##### Parameters
|Name|Description|
|---|---|
|result|The result to match on.|
|ok|Function called for the Ok case.|
|error|Function called for the Error case.|

#### Method <a name="M%3aMonacs.Core.Async.Result.MatchAsync%60%602(System.Threading.Tasks.Task%7bMonacs.Core.Result%7b%60%600%7d%7d%2cSystem.Func%7b%60%600%2c%60%601%7d%2cSystem.Func%7bMonacs.Core.ErrorDetails%2c%60%601%7d)"><code>MatchAsync</code></a>
 Does the pattern matching on the [<c>Result\`1</c>](#T%3aMonacs.Core.Result%601) type.             If the [<c>result</c>](#result) is Ok, calls [<c>ok</c>](#ok) function             with the value from the result as a parameter and returns its result.             Otherwise calls [<c>error</c>](#error) function and returns its result.







##### Generic parameters
|Name|Description|
|---|---|
|TIn|Type of the value in the result.|
|TOut|Type of the returned value.|

##### Parameters
|Name|Description|
|---|---|
|result|The result to match on.|
|ok|Function called for the Ok case.|
|error|Function called for the Error case.|

#### Method <a name="M%3aMonacs.Core.Async.Result.MatchAsync%60%602(System.Threading.Tasks.Task%7bMonacs.Core.Result%7b%60%600%7d%7d%2cSystem.Func%7b%60%600%2cSystem.Threading.Tasks.Task%7b%60%601%7d%7d%2cSystem.Func%7bMonacs.Core.ErrorDetails%2cSystem.Threading.Tasks.Task%7b%60%601%7d%7d)"><code>MatchAsync</code></a>
 Does the pattern matching on the [<c>Result\`1</c>](#T%3aMonacs.Core.Result%601) type.             If the [<c>result</c>](#result) is Ok, calls [<c>ok</c>](#ok) function             with the value from the result as a parameter and returns its result.             Otherwise calls [<c>error</c>](#error) function and returns its result.







##### Generic parameters
|Name|Description|
|---|---|
|TIn|Type of the value in the result.|
|TOut|Type of the returned value.|

##### Parameters
|Name|Description|
|---|---|
|result|The result to match on.|
|ok|Function called for the Ok case.|
|error|Function called for the Error case.|

#### Method <a name="M%3aMonacs.Core.Async.Result.MatchAsync%60%602(System.Threading.Tasks.Task%7bMonacs.Core.Result%7b%60%600%7d%7d%2cSystem.Func%7b%60%600%2cSystem.Threading.Tasks.Task%7b%60%601%7d%7d%2cSystem.Func%7bMonacs.Core.ErrorDetails%2c%60%601%7d)"><code>MatchAsync</code></a>
 Does the pattern matching on the [<c>Result\`1</c>](#T%3aMonacs.Core.Result%601) type.             If the [<c>result</c>](#result) is Ok, calls [<c>ok</c>](#ok) function             with the value from the result as a parameter and returns its result.             Otherwise calls [<c>error</c>](#error) function and returns its result.







##### Generic parameters
|Name|Description|
|---|---|
|TIn|Type of the value in the result.|
|TOut|Type of the returned value.|

##### Parameters
|Name|Description|
|---|---|
|result|The result to match on.|
|ok|Function called for the Ok case.|
|error|Function called for the Error case.|

#### Method <a name="M%3aMonacs.Core.Async.Result.MatchAsync%60%602(System.Threading.Tasks.Task%7bMonacs.Core.Result%7b%60%600%7d%7d%2cSystem.Func%7b%60%600%2c%60%601%7d%2cSystem.Func%7bMonacs.Core.ErrorDetails%2cSystem.Threading.Tasks.Task%7b%60%601%7d%7d)"><code>MatchAsync</code></a>
 Does the pattern matching on the [<c>Result\`1</c>](#T%3aMonacs.Core.Result%601) type.             If the [<c>result</c>](#result) is Ok, calls [<c>ok</c>](#ok) function             with the value from the result as a parameter and returns its result.             Otherwise calls [<c>error</c>](#error) function and returns its result.







##### Generic parameters
|Name|Description|
|---|---|
|TIn|Type of the value in the result.|
|TOut|Type of the returned value.|

##### Parameters
|Name|Description|
|---|---|
|result|The result to match on.|
|ok|Function called for the Ok case.|
|error|Function called for the Error case.|

#### Method <a name="M%3aMonacs.Core.Async.Result.IgnoreAsync%60%601(System.Threading.Tasks.Task%7bMonacs.Core.Result%7b%60%600%7d%7d)"><code>IgnoreAsync</code></a>
 Rejects the value of the [<c>Result\`1</c>](#T%3aMonacs.Core.Result%601) and returns [<c>Result\`1</c>](#T%3aMonacs.Core.Result%601) instead.              If the input [<c>Result\`1</c>](#T%3aMonacs.Core.Result%601) is Error then the error details are preserved.




##### Generic parameters
|Name|Description|
|---|---|
|T|Type of the encapsulated value.|

##### Parameters
|Name|Description|
|---|---|
|result|The result of which the value should be ignored.|

#### Method <a name="M%3aMonacs.Core.Async.Result.DoAsync%60%601(System.Threading.Tasks.Task%7bMonacs.Core.Result%7b%60%600%7d%7d%2cSystem.Action%7b%60%600%7d)"><code>DoAsync</code></a>
 Performs the [<c>action</c>](#action) with the value of the [<c>result</c>](#result) if it's Ok case.             If the result is Error case nothing happens.             In both cases unmodified result is returned.





##### Generic parameters
|Name|Description|
|---|---|
|T|Type of the value in the result.|

##### Parameters
|Name|Description|
|---|---|
|result|The result to check for a value.|
|action|Function executed if the result is Ok case.|

#### Method <a name="M%3aMonacs.Core.Async.Result.DoAsync%60%601(Monacs.Core.Result%7b%60%600%7d%2cSystem.Func%7b%60%600%2cSystem.Threading.Tasks.Task%7d)"><code>DoAsync</code></a>
 Performs the [<c>action</c>](#action) with the value of the [<c>result</c>](#result) if it's Ok case.             If the result is Error case nothing happens.             In both cases unmodified result is returned.





##### Generic parameters
|Name|Description|
|---|---|
|T|Type of the value in the result.|

##### Parameters
|Name|Description|
|---|---|
|result|The result to check for a value.|
|action|Function executed if the result is Ok case.|

#### Method <a name="M%3aMonacs.Core.Async.Result.DoAsync%60%601(System.Threading.Tasks.Task%7bMonacs.Core.Result%7b%60%600%7d%7d%2cSystem.Func%7b%60%600%2cSystem.Threading.Tasks.Task%7d)"><code>DoAsync</code></a>
 Performs the [<c>action</c>](#action) with the value of the [<c>result</c>](#result) if it's Ok case.             If the result is Error case nothing happens.             In both cases unmodified result is returned.





##### Generic parameters
|Name|Description|
|---|---|
|T|Type of the value in the result.|

##### Parameters
|Name|Description|
|---|---|
|result|The result to check for a value.|
|action|Function executed if the result is Ok case.|

#### Method <a name="M%3aMonacs.Core.Async.Result.DoWhenErrorAsync%60%601(System.Threading.Tasks.Task%7bMonacs.Core.Result%7b%60%600%7d%7d%2cSystem.Action%7bMonacs.Core.ErrorDetails%7d)"><code>DoWhenErrorAsync</code></a>
 Performs the [<c>action</c>](#action) if the [<c>result</c>](#result) is Error case.             If the result is Ok case nothing happens.             In both cases unmodified result is returned.





##### Generic parameters
|Name|Description|
|---|---|
|T|Type of the value in the result.|

##### Parameters
|Name|Description|
|---|---|
|result|The result to check for a value.|
|action|Function executed if the result is Error case.|

#### Method <a name="M%3aMonacs.Core.Async.Result.DoWhenErrorAsync%60%601(Monacs.Core.Result%7b%60%600%7d%2cSystem.Func%7bMonacs.Core.ErrorDetails%2cSystem.Threading.Tasks.Task%7d)"><code>DoWhenErrorAsync</code></a>
 Performs the [<c>action</c>](#action) if the [<c>result</c>](#result) is Error case.             If the result is Ok case nothing happens.             In both cases unmodified result is returned.





##### Generic parameters
|Name|Description|
|---|---|
|T|Type of the value in the result.|

##### Parameters
|Name|Description|
|---|---|
|result|The result to check for a value.|
|action|Function executed if the result is Error case.|

#### Method <a name="M%3aMonacs.Core.Async.Result.DoWhenErrorAsync%60%601(System.Threading.Tasks.Task%7bMonacs.Core.Result%7b%60%600%7d%7d%2cSystem.Func%7bMonacs.Core.ErrorDetails%2cSystem.Threading.Tasks.Task%7d)"><code>DoWhenErrorAsync</code></a>
 Performs the [<c>action</c>](#action) if the [<c>result</c>](#result) is Error case.             If the result is Ok case nothing happens.             In both cases unmodified result is returned.





##### Generic parameters
|Name|Description|
|---|---|
|T|Type of the value in the result.|

##### Parameters
|Name|Description|
|---|---|
|result|The result to check for a value.|
|action|Function executed if the result is Error case.|

#### Method <a name="M%3aMonacs.Core.Async.Result.FlipAsync%60%601(Monacs.Core.Result%7bSystem.Threading.Tasks.Task%7b%60%600%7d%7d)"><code>FlipAsync</code></a>
 Transforms [<c>Result\`1</c>](#T%3aMonacs.Core.Result%601) with async value inside to [<c>System.Threading.Tasks.Task\`1</c>](#T%3aSystem.Threading.Tasks.Task%601) of the result,             preserving original result's state and value.




##### Generic parameters
|Name|Description|
|---|---|
|T|Type of the value in the result.|

##### Parameters
|Name|Description|
|---|---|
|result|Result to take the value from.|

#### Method <a name="M%3aMonacs.Core.Async.Result.TryCatchAsync%60%601(System.Func%7bSystem.Threading.Tasks.Task%7b%60%600%7d%7d%2cSystem.Func%7bSystem.Exception%2cMonacs.Core.ErrorDetails%7d)"><code>TryCatchAsync</code></a>
 Tries to execute [<c>func</c>](#func) .             If the execution completes without exception, returns Ok with the function result.             Otherwise returns Error with details generated by [<c>errorHandler</c>](#errorHandler) based on the thrown exception.





##### Generic parameters
|Name|Description|
|---|---|
|T|Type of the value in the result.|

##### Parameters
|Name|Description|
|---|---|
|func|Function to execute.|
|errorHandler|Function that generates error details in case of exception.|

#### Method <a name="M%3aMonacs.Core.Async.Result.TryCatchAsync%60%602(Monacs.Core.Result%7b%60%600%7d%2cSystem.Func%7b%60%600%2cSystem.Threading.Tasks.Task%7b%60%601%7d%7d%2cSystem.Func%7b%60%600%2cSystem.Exception%2cMonacs.Core.ErrorDetails%7d)"><code>TryCatchAsync</code></a>
 Tries to execute [<c>func</c>](#func) with the value from the [<c>result</c>](#result) as an input.             If the execution completes without exception, returns Ok with the function result.             Otherwise returns Error with details generated by [<c>errorHandler</c>](#errorHandler) based on the thrown exception.             If the [<c>result</c>](#result) is Error function is not executed and the Error is returned.







##### Generic parameters
|Name|Description|
|---|---|
|TIn|Type of the value in the input result.|
|TOut|Type of the value in the output result.|

##### Parameters
|Name|Description|
|---|---|
|result|Result to take the value from.|
|func|Function to execute.|
|errorHandler|Function that generates error details in case of exception.|


## Type <a name="T%3aMonacs.Core.ErrorDetails"><code>Monacs.Core.ErrorDetails</code></a>
 Represents the details of the error in case of failed operation.             To create the instances use the factory methods from the [<c>Errors</c>](#T%3aMonacs.Core.Errors) class.


### Properties
#### Property <a name="P%3aMonacs.Core.ErrorDetails.Level"><code>Level</code></a>
 Contains the error severity described by [<c>ErrorLevel</c>](#T%3aMonacs.Core.ErrorLevel) .


#### Property <a name="P%3aMonacs.Core.ErrorDetails.Message"><code>Message</code></a>
 Contains optional message to describe the error details.


#### Property <a name="P%3aMonacs.Core.ErrorDetails.Key"><code>Key</code></a>
 Contains optional error key to identify the error.


#### Property <a name="P%3aMonacs.Core.ErrorDetails.Exception"><code>Exception</code></a>
 Contains optional exception which operation ended up with.             Set to None if no exception occured.


#### Property <a name="P%3aMonacs.Core.ErrorDetails.Metadata"><code>Metadata</code></a>
 Contains optional error metadata.



## Type <a name="T%3aMonacs.Core.ErrorLevel"><code>Monacs.Core.ErrorLevel</code></a>
 Represents the severity of the error.


### Fields
#### Field <a name="F%3aMonacs.Core.ErrorLevel.Trace"><code>Trace</code></a>



## Type <a name="T%3aMonacs.Core.Errors"><code>Monacs.Core.Errors</code></a>
 Contains factory methods to create instances of [<c>ErrorDetails</c>](#T%3aMonacs.Core.ErrorDetails) in a more convenient way.


### Methods
#### Method <a name="M%3aMonacs.Core.Errors.Trace(System.String%2cSystem.String%2cSystem.Exception%2cSystem.Object)"><code>Trace</code></a>
 Creates [<c>ErrorDetails</c>](#T%3aMonacs.Core.ErrorDetails) with level [<c>ErrorLevel.Trace</c>](#F%3aMonacs.Core.ErrorLevel.Trace) .







##### Parameters
|Name|Description|
|---|---|
|message|Optional error message|
|key|Optional key to identify the error|
|exception|Optional exception which caused the error|
|metadata|Optional error metadata|

#### Method <a name="M%3aMonacs.Core.Errors.Debug(System.String%2cSystem.String%2cSystem.Exception%2cSystem.Object)"><code>Debug</code></a>
 Creates [<c>ErrorDetails</c>](#T%3aMonacs.Core.ErrorDetails) with level [<c>ErrorLevel.Debug</c>](#F%3aMonacs.Core.ErrorLevel.Debug) .







##### Parameters
|Name|Description|
|---|---|
|message|Optional error message|
|key|Optional key to identify the error|
|exception|Optional exception which caused the error|
|metadata|Optional error metadata|

#### Method <a name="M%3aMonacs.Core.Errors.Info(System.String%2cSystem.String%2cSystem.Exception%2cSystem.Object)"><code>Info</code></a>
 Creates [<c>ErrorDetails</c>](#T%3aMonacs.Core.ErrorDetails) with level [<c>ErrorLevel.Info</c>](#F%3aMonacs.Core.ErrorLevel.Info) .







##### Parameters
|Name|Description|
|---|---|
|message|Optional error message|
|key|Optional key to identify the error|
|exception|Optional exception which caused the error|
|metadata|Optional error metadata|

#### Method <a name="M%3aMonacs.Core.Errors.Warn(System.String%2cSystem.String%2cSystem.Exception%2cSystem.Object)"><code>Warn</code></a>
 Creates [<c>ErrorDetails</c>](#T%3aMonacs.Core.ErrorDetails) with level [<c>ErrorLevel.Warn</c>](#F%3aMonacs.Core.ErrorLevel.Warn) .







##### Parameters
|Name|Description|
|---|---|
|message|Optional error message|
|key|Optional key to identify the error|
|exception|Optional exception which caused the error|
|metadata|Optional error metadata|

#### Method <a name="M%3aMonacs.Core.Errors.Error(System.String%2cSystem.String%2cSystem.Exception%2cSystem.Object)"><code>Error</code></a>
 Creates [<c>ErrorDetails</c>](#T%3aMonacs.Core.ErrorDetails) with level [<c>ErrorLevel.Error</c>](#F%3aMonacs.Core.ErrorLevel.Error) .







##### Parameters
|Name|Description|
|---|---|
|message|Optional error message|
|key|Optional key to identify the error|
|exception|Optional exception which caused the error|
|metadata|Optional error metadata|

#### Method <a name="M%3aMonacs.Core.Errors.Fatal(System.String%2cSystem.String%2cSystem.Exception%2cSystem.Object)"><code>Fatal</code></a>
 Creates [<c>ErrorDetails</c>](#T%3aMonacs.Core.ErrorDetails) with level [<c>ErrorLevel.Fatal</c>](#F%3aMonacs.Core.ErrorLevel.Fatal) .







##### Parameters
|Name|Description|
|---|---|
|message|Optional error message|
|key|Optional key to identify the error|
|exception|Optional exception which caused the error|
|metadata|Optional error metadata|


## Type <a name="T%3aMonacs.Core.Option%601"><code>Monacs.Core.Option&lt;T&gt;</code></a>
 Encapsulates optional value.             It is recommended to use provided extension methods and not to use properties of the [<c>Option\`1</c>](#T%3aMonacs.Core.Option%601) directly. 

 The Option can contain a value of a type [<c>T</c>](#T) and it's called Some in such case. 

 If no value is encapsulated it's called None.


### Generic parameters
|Name|Description|
|---|---|
|T|Type of encapsulated value.|

### Methods
#### Method <a name="M%3aMonacs.Core.Option%601.ToString"><code>ToString</code></a>
 Creates a string representation of the [<c>Option\`1</c>](#T%3aMonacs.Core.Option%601) .




#### Method <a name="M%3aMonacs.Core.Option%601.Equals(Monacs.Core.Option%7b%600%7d)"><code>Equals</code></a>
 Compares two instances of the [<c>Option\`1</c>](#T%3aMonacs.Core.Option%601) .             Two options are equal if both are of the same type, the same case             and the underlying values are equal.




##### Parameters
|Name|Description|
|---|---|
|other|Option to compare with|

#### Method <a name="M%3aMonacs.Core.Option%601.Equals(%600)"><code>Equals</code></a>
 Compares [<c>Option\`1</c>](#T%3aMonacs.Core.Option%601) with the value of type [<c>T</c>](#T) .             Option is equal to the value of the underlying type if it's Some case             and encapsulated value is equal to [<c>other</c>](#other) value.




##### Parameters
|Name|Description|
|---|---|
|other|Option to compare with|

#### Method <a name="M%3aMonacs.Core.Option%601.Equals(System.Object)"><code>Equals</code></a>
 Compares the [<c>Option\`1</c>](#T%3aMonacs.Core.Option%601) with other object.             Option is only equal to other option given the conditions described in [<c>Option\`1.Equals(Option{\`0})</c>](#M%3aMonacs.Core.Option%601.Equals(Monacs.Core.Option%7b%600%7d)) .




##### Parameters
|Name|Description|
|---|---|
|obj|Object to compare with|

#### Method <a name="M%3aMonacs.Core.Option%601.GetHashCode"><code>GetHashCode</code></a>
 Computes the hashcode for the [<c>Option\`1</c>](#T%3aMonacs.Core.Option%601) instance.





### Properties
#### Property <a name="P%3aMonacs.Core.Option%601.Value"><code>Value</code></a>
 Encapsulated value. Will be default(T) in None case. 

 It is not recommended to use it directly. 

 Use extension methods to access the value instead, like: 

 * [<c>Option.GetOrDefault\`\`1(Option{\`\`0},\`\`0)</c>](#M%3aMonacs.Core.Option.GetOrDefault%60%601(Monacs.Core.Option%7b%60%600%7d%2c%60%600)) , 

 * [<c>Option.Map\`\`2(Option{\`\`0},System.Func{\`\`0,\`\`1})</c>](#M%3aMonacs.Core.Option.Map%60%602(Monacs.Core.Option%7b%60%600%7d%2cSystem.Func%7b%60%600%2c%60%601%7d)) , 

 * [<c>Option.Bind\`\`2(Option{\`\`0},System.Func{\`\`0,Option{\`\`1}})</c>](#M%3aMonacs.Core.Option.Bind%60%602(Monacs.Core.Option%7b%60%600%7d%2cSystem.Func%7b%60%600%2cMonacs.Core.Option%7b%60%601%7d%7d)) , 

 * [<c>Option.Match\`\`2(Option{\`\`0},System.Func{\`\`0,\`\`1},System.Func{\`\`1})</c>](#M%3aMonacs.Core.Option.Match%60%602(Monacs.Core.Option%7b%60%600%7d%2cSystem.Func%7b%60%600%2c%60%601%7d%2cSystem.Func%7b%60%601%7d))


#### Property <a name="P%3aMonacs.Core.Option%601.IsSome"><code>IsSome</code></a>
 Returns true if the option has value (is Some case).


#### Property <a name="P%3aMonacs.Core.Option%601.IsNone"><code>IsNone</code></a>
 Returns true if the option has no value (is None case).



## Type <a name="T%3aMonacs.Core.Option"><code>Monacs.Core.Option</code></a>
 Contains the set of extensions to work with the [<c>Option\`1</c>](#T%3aMonacs.Core.Option%601) type.


### Methods
#### Method <a name="M%3aMonacs.Core.Option.Some%60%601(%60%600)"><code>Some</code></a>
 Creates the Some case instance of the [<c>Option\`1</c>](#T%3aMonacs.Core.Option%601) type, encapsulating provided value.




##### Generic parameters
|Name|Description|
|---|---|
|T|Type of the encapsulated value.|

##### Parameters
|Name|Description|
|---|---|
|value|The value to encapsulate.|

#### Method <a name="M%3aMonacs.Core.Option.None%60%601"><code>None</code></a>
 Creates the None case instance of the [<c>Option\`1</c>](#T%3aMonacs.Core.Option%601) type, containing no value.



##### Generic parameters
|Name|Description|
|---|---|
|T|Desired type parameter for  type.|


#### Method <a name="M%3aMonacs.Core.Option.OfObject%60%601(%60%600)"><code>OfObject</code></a>
 Converts the value of class T to the [<c>Option\`1</c>](#T%3aMonacs.Core.Option%601) type.             If the value is null, the None case is yielded.             Otherwise Some case with provided value is returned.




##### Generic parameters
|Name|Description|
|---|---|
|T|Type of the encapsulated value.|

##### Parameters
|Name|Description|
|---|---|
|value|The value to convert to .|

#### Method <a name="M%3aMonacs.Core.Option.ToOption%60%601(%60%600)"><code>ToOption</code></a>
 Converts the value of class T to the [<c>Option\`1</c>](#T%3aMonacs.Core.Option%601) type.             If the value is null, the None case is yielded.             Otherwise Some case with provided value is returned.

*Remarks:* Extension method variant of [<c>Option.OfObject\`\`1(\`\`0)</c>](#M%3aMonacs.Core.Option.OfObject%60%601(%60%600))




##### Generic parameters
|Name|Description|
|---|---|
|T|Type of the encapsulated value.|

##### Parameters
|Name|Description|
|---|---|
|value|The value to convert to .|

#### Method <a name="M%3aMonacs.Core.Option.OfNullable%60%601(System.Nullable%7b%60%600%7d)"><code>OfNullable</code></a>
 Converts the value of [<c>System.Nullable\`1</c>](#T%3aSystem.Nullable%601) to the [<c>Option\`1</c>](#T%3aMonacs.Core.Option%601) type.             If the value is null, the None case is yielded.             Otherwise Some case with provided value is returned.




##### Generic parameters
|Name|Description|
|---|---|
|T|Type of the encapsulated value.|

##### Parameters
|Name|Description|
|---|---|
|value|The value to convert to .|

#### Method <a name="M%3aMonacs.Core.Option.ToOption%60%601(System.Nullable%7b%60%600%7d)"><code>ToOption</code></a>
 Converts the value of [<c>System.Nullable\`1</c>](#T%3aSystem.Nullable%601) to the [<c>Option\`1</c>](#T%3aMonacs.Core.Option%601) type.             If the value is null, the None case is yielded.             Otherwise Some case with provided value is returned.

*Remarks:* Extension method variant of [<c>Option.OfNullable\`\`1(System.Nullable{\`\`0})</c>](#M%3aMonacs.Core.Option.OfNullable%60%601(System.Nullable%7b%60%600%7d))




##### Generic parameters
|Name|Description|
|---|---|
|T|Type of the encapsulated value.|

##### Parameters
|Name|Description|
|---|---|
|value|The value to convert to .|

#### Method <a name="M%3aMonacs.Core.Option.ToNullable%60%601(Monacs.Core.Option%7b%60%600%7d)"><code>ToNullable</code></a>
 Converts the value of [<c>Option\`1</c>](#T%3aMonacs.Core.Option%601) to the [<c>System.Nullable\`1</c>](#T%3aSystem.Nullable%601) type.             If the option is the None case, null is yielded.             Otherwise encapsulated value is returned.




##### Generic parameters
|Name|Description|
|---|---|
|T|Type of the encapsulated value.|

##### Parameters
|Name|Description|
|---|---|
|value|The value to convert to .|

#### Method <a name="M%3aMonacs.Core.Option.OfString(System.String)"><code>OfString</code></a>
 Converts the string value to the [<c>Option\`1</c>](#T%3aMonacs.Core.Option%601) type.             If the value is null or empty string, the None case is yielded.             Otherwise Some case with provided value is returned.




##### Parameters
|Name|Description|
|---|---|
|value|The value to convert to .|

#### Method <a name="M%3aMonacs.Core.Option.ToOption(System.String)"><code>ToOption</code></a>
 Converts the string value to the [<c>Option{string}</c>](#T%3aOption%7bstring%7d) type.             If the value is null or empty string, the None case is yielded.             Otherwise Some case with provided value is returned.

*Remarks:* Extension method variant of [<c>Option.OfString(System.String)</c>](#M%3aMonacs.Core.Option.OfString(System.String))




##### Parameters
|Name|Description|
|---|---|
|value|The value to convert to .|

#### Method <a name="M%3aMonacs.Core.Option.OfResult%60%601(Monacs.Core.Result%7b%60%600%7d)"><code>OfResult</code></a>
 Converts the value of [<c>Result\`1</c>](#T%3aMonacs.Core.Result%601) to the [<c>Option\`1</c>](#T%3aMonacs.Core.Option%601) type.             If the value is the Error case, the None case is yielded.             Otherwise Some case with encapsulated value is returned.




##### Generic parameters
|Name|Description|
|---|---|
|T|Type of the encapsulated value.|

##### Parameters
|Name|Description|
|---|---|
|value|The value to convert to .|

#### Method <a name="M%3aMonacs.Core.Option.ToOption%60%601(Monacs.Core.Result%7b%60%600%7d)"><code>ToOption</code></a>
 Converts the value of [<c>Result\`1</c>](#T%3aMonacs.Core.Result%601) to the [<c>Option\`1</c>](#T%3aMonacs.Core.Option%601) type.             If the value is the Error case, the None case is yielded.             Otherwise Some case with encapsulated value is returned.

*Remarks:* Extension method variant of [<c>Option.OfResult\`\`1(Result{\`\`0})</c>](#M%3aMonacs.Core.Option.OfResult%60%601(Monacs.Core.Result%7b%60%600%7d))




##### Generic parameters
|Name|Description|
|---|---|
|T|Type of the encapsulated value.|

##### Parameters
|Name|Description|
|---|---|
|value|The value to convert to .|

#### Method <a name="M%3aMonacs.Core.Option.TryGetOption%60%602(System.Collections.Generic.IDictionary%7b%60%600%2c%60%601%7d%2c%60%600)"><code>TryGetOption</code></a>
 Tries to get the element with the given [<c>key</c>](#key) from the [<c>dictionary</c>](#dictionary) .             If the value is found, returns Some case of the [<c>Option\`1</c>](#T%3aMonacs.Core.Option%601) type with the value from the dictionary.             Otherwise returns None case of the [<c>Option\`1</c>](#T%3aMonacs.Core.Option%601) type.






##### Generic parameters
|Name|Description|
|---|---|
|TKey|Type of the key in the dictionary.|
|TValue|Type of the value in the dictionary.|

##### Parameters
|Name|Description|
|---|---|
|dictionary|The dictionary to search in.|
|key|The key to look for.|

#### Method <a name="M%3aMonacs.Core.Option.TryGetOption%60%602(System.Linq.ILookup%7b%60%600%2c%60%601%7d%2c%60%600)"><code>TryGetOption</code></a>
 Tries to get the elements with the given [<c>key</c>](#key) from the [<c>lookup</c>](#lookup) .             If any value is found, returns Some case of the [<c>Option\`1</c>](#T%3aMonacs.Core.Option%601) type with the values from the lookup.             Otherwise returns None case of the [<c>Option\`1</c>](#T%3aMonacs.Core.Option%601) type.






##### Generic parameters
|Name|Description|
|---|---|
|TKey|Type of the key in the lookup.|
|TValue|Type of the value in the lookup.|

##### Parameters
|Name|Description|
|---|---|
|lookup|The lookup to search in.|
|key|The key to look for.|

#### Method <a name="M%3aMonacs.Core.Option.Match%60%602(Monacs.Core.Option%7b%60%600%7d%2cSystem.Func%7b%60%600%2c%60%601%7d%2cSystem.Func%7b%60%601%7d)"><code>Match</code></a>
 Does the pattern matching on the [<c>Option\`1</c>](#T%3aMonacs.Core.Option%601) type.             If the [<c>option</c>](#option) is Some, calls [<c>some</c>](#some) function             with the value from the option as a parameter and returns its result.             Otherwise calls [<c>none</c>](#none) function and returns its result.







##### Generic parameters
|Name|Description|
|---|---|
|TIn|Type of the value in the option.|
|TOut|Type of the returned value.|

##### Parameters
|Name|Description|
|---|---|
|option|The option to match on.|
|some|Function called for the Some case.|
|none|Function called for the None case.|

#### Method <a name="M%3aMonacs.Core.Option.MatchTo%60%602(Monacs.Core.Option%7b%60%600%7d%2c%60%601%2c%60%601)"><code>MatchTo</code></a>
 Does the pattern matching on the [<c>Option\`1</c>](#T%3aMonacs.Core.Option%601) type.             If the [<c>option</c>](#option) is Some, returns [<c>some</c>](#some) value.             Otherwise returns [<c>none</c>](#none) value.







##### Generic parameters
|Name|Description|
|---|---|
|TIn|Type of the value in the option.|
|TOut|Type of the returned value.|

##### Parameters
|Name|Description|
|---|---|
|option|The option to match on.|
|some|Value returned for the Some case.|
|none|Value returned for the None case.|

#### Method <a name="M%3aMonacs.Core.Option.Bind%60%602(Monacs.Core.Option%7b%60%600%7d%2cSystem.Func%7b%60%600%2cMonacs.Core.Option%7b%60%601%7d%7d)"><code>Bind</code></a>
 Transforms the [<c>option</c>](#option) into another [<c>Option\`1</c>](#T%3aMonacs.Core.Option%601) using the [<c>binder</c>](#binder) function.             If the input option is Some, returns the value of the binder call (which is [<c>TOut</c>](#TOut) option).             Otherwise returns None case of the [<c>TOut</c>](#TOut) option.






##### Generic parameters
|Name|Description|
|---|---|
|TIn|Type of the value in the input option.|
|TOut|Type of the value in the returned option.|

##### Parameters
|Name|Description|
|---|---|
|option|The option to bind with.|
|binder|Function called with the input option value if it's Some case.|

#### Method <a name="M%3aMonacs.Core.Option.Map%60%602(Monacs.Core.Option%7b%60%600%7d%2cSystem.Func%7b%60%600%2c%60%601%7d)"><code>Map</code></a>
 Maps the value of the [<c>option</c>](#option) into another [<c>Option\`1</c>](#T%3aMonacs.Core.Option%601) using the [<c>mapper</c>](#mapper) function.             If the input option is Some, returns the Some case with the value of the mapper call (which is [<c>TOut</c>](#TOut) ).             Otherwise returns None case of the [<c>TOut</c>](#TOut) option.






##### Generic parameters
|Name|Description|
|---|---|
|TIn|Type of the value in the input option.|
|TOut|Type of the value in the returned option.|

##### Parameters
|Name|Description|
|---|---|
|option|The option to map on.|
|mapper|Function called with the input option value if it's Some case.|

#### Method <a name="M%3aMonacs.Core.Option.GetOrDefault%60%601(Monacs.Core.Option%7b%60%600%7d%2c%60%600)"><code>GetOrDefault</code></a>
 Gets the value of the [<c>option</c>](#option) if it's Some case.             If the option is None case returns value specified by the [<c>whenNone</c>](#whenNone) parameter;             if the parameter is not set returns the default value of the type [<c>T</c>](#T) .





##### Generic parameters
|Name|Description|
|---|---|
|T|Type of the value in the option.|

##### Parameters
|Name|Description|
|---|---|
|option|The option to get a value from.|
|whenNone|Value to return if the option is the None case.|

#### Method <a name="M%3aMonacs.Core.Option.GetOrDefault%60%602(Monacs.Core.Option%7b%60%600%7d%2cSystem.Func%7b%60%600%2c%60%601%7d%2c%60%601)"><code>GetOrDefault</code></a>
 Gets the value from the [<c>option</c>](#option) using the [<c>getter</c>](#getter) function if it's Some case.             If the option is None case returns value specified by the [<c>whenNone</c>](#whenNone) parameter;             if the parameter is not set returns the default value of the type [<c>TOut</c>](#TOut) .

*Remarks:* Effectively the combination of [<c>Option.Map\`\`2(Option{\`\`0},System.Func{\`\`0,\`\`1})</c>](#M%3aMonacs.Core.Option.Map%60%602(Monacs.Core.Option%7b%60%600%7d%2cSystem.Func%7b%60%600%2c%60%601%7d)) and [<c>Option.GetOrDefault\`\`1(Option{\`\`0},\`\`0)</c>](#M%3aMonacs.Core.Option.GetOrDefault%60%601(Monacs.Core.Option%7b%60%600%7d%2c%60%600)) calls.







##### Generic parameters
|Name|Description|
|---|---|
|TIn|Type of the value in the option.|
|TOut|Type of the return value.|

##### Parameters
|Name|Description|
|---|---|
|option|The option to get a value from.|
|getter|Function used to get the value if the option is the Some case.|
|whenNone|Value to return if the option is the None case.|

#### Method <a name="M%3aMonacs.Core.Option.Do%60%601(Monacs.Core.Option%7b%60%600%7d%2cSystem.Action%7b%60%600%7d)"><code>Do</code></a>
 Performs the [<c>action</c>](#action) with the value of the [<c>option</c>](#option) if it's Some case.             If the option is None case nothing happens.             In both cases unmodified option is returned.





##### Generic parameters
|Name|Description|
|---|---|
|T|Type of the value in the option.|

##### Parameters
|Name|Description|
|---|---|
|option|The option to check for a value.|
|action|Function executed if the option is Some case.|

#### Method <a name="M%3aMonacs.Core.Option.DoWhenNone%60%601(Monacs.Core.Option%7b%60%600%7d%2cSystem.Action)"><code>DoWhenNone</code></a>
 Performs the [<c>action</c>](#action) if the [<c>option</c>](#option) is None case.             If the option is Some case nothing happens.             In both cases unmodified option is returned.





##### Generic parameters
|Name|Description|
|---|---|
|T|Type of the value in the option.|

##### Parameters
|Name|Description|
|---|---|
|option|The option to check for a value.|
|action|Function executed if the option is None case.|

#### Method <a name="M%3aMonacs.Core.Option.Choose%60%601(System.Collections.Generic.IEnumerable%7bMonacs.Core.Option%7b%60%600%7d%7d)"><code>Choose</code></a>
 Returns the collection of values of elements from the [<c>Option\`1</c>](#T%3aMonacs.Core.Option%601) collection             that are Some case (so contain some value).




##### Generic parameters
|Name|Description|
|---|---|
|T|Type of the value in the option.|

##### Parameters
|Name|Description|
|---|---|
|items|Collection to filter out and map.|

#### Method <a name="M%3aMonacs.Core.Option.Sequence%60%601(System.Collections.Generic.IEnumerable%7bMonacs.Core.Option%7b%60%600%7d%7d)"><code>Sequence</code></a>
 If all elements in the input collection are Some case, returns the Some of the collection of underlying values.             Otherwise returns None.




##### Generic parameters
|Name|Description|
|---|---|
|T|Type of the value in the option.|

##### Parameters
|Name|Description|
|---|---|
|items|Collection to check and map.|

#### Method <a name="M%3aMonacs.Core.Option.TryFind%60%601(System.Collections.Generic.IEnumerable%7b%60%600%7d%2cSystem.Func%7b%60%600%2cSystem.Boolean%7d)"><code>TryFind</code></a>
 Tries to find the first element of the [<c>items</c>](#items) collection matching the [<c>predicate</c>](#predicate) .             If element is found, returns Some with the value of that element.             Otherwise returns None.





##### Generic parameters
|Name|Description|
|---|---|
|T|Type of the value in the collection and returned option.|

##### Parameters
|Name|Description|
|---|---|
|items|Collection to search in.|
|predicate|Function that checks if given element matches desired condition.|

#### Method <a name="M%3aMonacs.Core.Option.TryFirst%60%601(System.Collections.Generic.IEnumerable%7b%60%600%7d)"><code>TryFirst</code></a>
 Tries to get the the element in the [<c>items</c>](#items) collection.             If element is found, returns Some with the value of that element.             Otherwise returns None.




##### Generic parameters
|Name|Description|
|---|---|
|T|Type of the value in the collection and the returned option.|

##### Parameters
|Name|Description|
|---|---|
|items|Collection to search in.|

#### Method <a name="M%3aMonacs.Core.Option.TryElementAt%60%601(System.Collections.Generic.IEnumerable%7b%60%600%7d%2cSystem.Int32)"><code>TryElementAt</code></a>
 Tries to get the element of the [<c>items</c>](#items) collection at the posision given by the [<c>index</c>](#index) parameter.             If element is found, returns Some with the value of that element.             Otherwise returns None.





##### Generic parameters
|Name|Description|
|---|---|
|T|Type of the value in the collection and returned option.|

##### Parameters
|Name|Description|
|---|---|
|items|Collection to search in.|
|index|Position at which to look for an element.|


## Type <a name="T%3aMonacs.Core.Result%601"><code>Monacs.Core.Result&lt;T&gt;</code></a>
 Represents the result of the operation that may succeed or fail.             It is recommended to use provided extension methods and not to use properties of the [<c>Result\`1</c>](#T%3aMonacs.Core.Result%601) directly. 

 If the operation succeeded it will contain a value of a type [<c>T</c>](#T) and it's called Ok in such case. 

 If the operation failed it will contain error information of type [<c>ErrorDetails</c>](#T%3aMonacs.Core.ErrorDetails) and it's called Error.


### Generic parameters
|Name|Description|
|---|---|
|T|Expected return value type.|

### Methods
#### Method <a name="M%3aMonacs.Core.Result%601.ToString"><code>ToString</code></a>
 Creates a string representation of the [<c>Result\`1</c>](#T%3aMonacs.Core.Result%601) .




#### Method <a name="M%3aMonacs.Core.Result%601.Equals(Monacs.Core.Result%7b%600%7d)"><code>Equals</code></a>
 Compares two instances of the [<c>Result\`1</c>](#T%3aMonacs.Core.Result%601) .             Two results are equal if both are of the same type, the same case             and the underlying values (of errors) are equal.




##### Parameters
|Name|Description|
|---|---|
|other|Result to compare with|

#### Method <a name="M%3aMonacs.Core.Result%601.Equals(System.Object)"><code>Equals</code></a>
 Compares the [<c>Result\`1</c>](#T%3aMonacs.Core.Result%601) with other object.             Result is only equal to other result given the conditions described in [<c>Result\`1.Equals(Result{\`0})</c>](#M%3aMonacs.Core.Result%601.Equals(Monacs.Core.Result%7b%600%7d)) .




##### Parameters
|Name|Description|
|---|---|
|obj|Object to compare with|

#### Method <a name="M%3aMonacs.Core.Result%601.GetHashCode"><code>GetHashCode</code></a>
 Computes the hashcode for the [<c>Result\`1</c>](#T%3aMonacs.Core.Result%601) instance.





### Properties
#### Property <a name="P%3aMonacs.Core.Result%601.Value"><code>Value</code></a>
 Contains the computed value of the operation if it ends successfully. 

 It is not recommended to use it directly. 

 Use extension methods to access the value instead, like: 

 * [<c>Result.GetOrDefault\`\`1(Result{\`\`0},\`\`0)</c>](#M%3aMonacs.Core.Result.GetOrDefault%60%601(Monacs.Core.Result%7b%60%600%7d%2c%60%600)) , 

 * [<c>Result.Map\`\`2(Result{\`\`0},System.Func{\`\`0,\`\`1})</c>](#M%3aMonacs.Core.Result.Map%60%602(Monacs.Core.Result%7b%60%600%7d%2cSystem.Func%7b%60%600%2c%60%601%7d)) , 

 * [<c>Result.Bind\`\`2(Result{\`\`0},System.Func{\`\`0,Result{\`\`1}})</c>](#M%3aMonacs.Core.Result.Bind%60%602(Monacs.Core.Result%7b%60%600%7d%2cSystem.Func%7b%60%600%2cMonacs.Core.Result%7b%60%601%7d%7d)) , 

 * [<c>Result.Match\`\`2(Result{\`\`0},System.Func{\`\`0,\`\`1},System.Func{ErrorDetails,\`\`1})</c>](#M%3aMonacs.Core.Result.Match%60%602(Monacs.Core.Result%7b%60%600%7d%2cSystem.Func%7b%60%600%2c%60%601%7d%2cSystem.Func%7bMonacs.Core.ErrorDetails%2c%60%601%7d))


#### Property <a name="P%3aMonacs.Core.Result%601.Error"><code>Error</code></a>
 Contains error details when operation ended up with failure. 

 It is not recommended to use it directly. 

 Use extension methods to access the value instead, like: 

 * [<c>Result.Match\`\`2(Result{\`\`0},System.Func{\`\`0,\`\`1},System.Func{ErrorDetails,\`\`1})</c>](#M%3aMonacs.Core.Result.Match%60%602(Monacs.Core.Result%7b%60%600%7d%2cSystem.Func%7b%60%600%2c%60%601%7d%2cSystem.Func%7bMonacs.Core.ErrorDetails%2c%60%601%7d)) 

 * [<c>Result.DoWhenError\`\`1(Result{\`\`0},System.Action{ErrorDetails})</c>](#M%3aMonacs.Core.Result.DoWhenError%60%601(Monacs.Core.Result%7b%60%600%7d%2cSystem.Action%7bMonacs.Core.ErrorDetails%7d))


#### Property <a name="P%3aMonacs.Core.Result%601.IsOk"><code>IsOk</code></a>
 Indicates that the Result is on the success path (Ok case).             You should expect the output in the [<c>Result\`1.Value</c>](#P%3aMonacs.Core.Result%601.Value) field.


#### Property <a name="P%3aMonacs.Core.Result%601.IsError"><code>IsError</code></a>
 Indicates that the result is on the failure path (Error case).             You should expect error in [<c>Result\`1.Error</c>](#P%3aMonacs.Core.Result%601.Error) field             and no value in the [<c>Result\`1.Value</c>](#P%3aMonacs.Core.Result%601.Value) field.



## Type <a name="T%3aMonacs.Core.Result"><code>Monacs.Core.Result</code></a>
 Contains the set of extensions to work with the [<c>Result\`1</c>](#T%3aMonacs.Core.Result%601) type.


### Methods
#### Method <a name="M%3aMonacs.Core.Result.Ok%60%601(%60%600)"><code>Ok</code></a>
 Creates the Ok case instance of the [<c>Result\`1</c>](#T%3aMonacs.Core.Result%601) type, encapsulating provided value.




##### Generic parameters
|Name|Description|
|---|---|
|T|Type of the encapsulated value.|

##### Parameters
|Name|Description|
|---|---|
|value|The value to encapsulate.|

#### Method <a name="M%3aMonacs.Core.Result.Error%60%601(Monacs.Core.ErrorDetails)"><code>Error</code></a>
 Creates the Error case instance of the [<c>Result\`1</c>](#T%3aMonacs.Core.Result%601) type, containing error instead of value.




##### Generic parameters
|Name|Description|
|---|---|
|T|Desired type parameter for  type.|

##### Parameters
|Name|Description|
|---|---|
|error|Details of the error.|

#### Method <a name="M%3aMonacs.Core.Result.OfObject%60%601(%60%600%2cMonacs.Core.ErrorDetails)"><code>OfObject</code></a>
 Converts the value of class T to the [<c>Result\`1</c>](#T%3aMonacs.Core.Result%601) type.             If the value is null, the Error case is yielded.             Otherwise Ok case with provided value is returned.





##### Generic parameters
|Name|Description|
|---|---|
|T|Type of the encapsulated value.|

##### Parameters
|Name|Description|
|---|---|
|value|The value to convert to .|
|error|Details of the error if the value is null.|

#### Method <a name="M%3aMonacs.Core.Result.OfObject%60%601(%60%600%2cSystem.Func%7bMonacs.Core.ErrorDetails%7d)"><code>OfObject</code></a>
 Converts the value of class T to the [<c>Result\`1</c>](#T%3aMonacs.Core.Result%601) type.             If the value is null, the Error case is yielded.             Otherwise Ok case with provided value is returned.





##### Generic parameters
|Name|Description|
|---|---|
|T|Type of the encapsulated value.|

##### Parameters
|Name|Description|
|---|---|
|value|The value to convert to .|
|errorFunc|Function yielding details of the error if the value is null.|

#### Method <a name="M%3aMonacs.Core.Result.ToResult%60%601(%60%600%2cMonacs.Core.ErrorDetails)"><code>ToResult</code></a>
 Converts the value of class T to the [<c>Result\`1</c>](#T%3aMonacs.Core.Result%601) type.             If the value is null, the Error case is yielded.             Otherwise Ok case with provided value is returned.

*Remarks:* Extension method variant of [<c>Result.OfObject\`\`1(\`\`0,ErrorDetails)</c>](#M%3aMonacs.Core.Result.OfObject%60%601(%60%600%2cMonacs.Core.ErrorDetails))





##### Generic parameters
|Name|Description|
|---|---|
|T|Type of the encapsulated value.|

##### Parameters
|Name|Description|
|---|---|
|value|The value to convert to .|
|error|Details of the error if the value is null.|

#### Method <a name="M%3aMonacs.Core.Result.ToResult%60%601(%60%600%2cSystem.Func%7bMonacs.Core.ErrorDetails%7d)"><code>ToResult</code></a>
 Converts the value of class T to the [<c>Result\`1</c>](#T%3aMonacs.Core.Result%601) type.             If the value is null, the Error case is yielded.             Otherwise Ok case with provided value is returned.

*Remarks:* Extension method variant of [<c>Result.OfObject\`\`1(\`\`0,System.Func{ErrorDetails})</c>](#M%3aMonacs.Core.Result.OfObject%60%601(%60%600%2cSystem.Func%7bMonacs.Core.ErrorDetails%7d))





##### Generic parameters
|Name|Description|
|---|---|
|T|Type of the encapsulated value.|

##### Parameters
|Name|Description|
|---|---|
|value|The value to convert to .|
|errorFunc|Function yielding details of the error if the value is null.|

#### Method <a name="M%3aMonacs.Core.Result.OfNullable%60%601(System.Nullable%7b%60%600%7d%2cMonacs.Core.ErrorDetails)"><code>OfNullable</code></a>
 Converts the value of [<c>System.Nullable\`1</c>](#T%3aSystem.Nullable%601) to the [<c>Result\`1</c>](#T%3aMonacs.Core.Result%601) type.             If the value is null, the Error case is yielded.             Otherwise Ok case with provided value is returned.





##### Generic parameters
|Name|Description|
|---|---|
|T|Type of the encapsulated value.|

##### Parameters
|Name|Description|
|---|---|
|value|The value to convert to .|
|error|Details of the error if the value is null.|

#### Method <a name="M%3aMonacs.Core.Result.OfNullable%60%601(System.Nullable%7b%60%600%7d%2cSystem.Func%7bMonacs.Core.ErrorDetails%7d)"><code>OfNullable</code></a>
 Converts the value of [<c>System.Nullable\`1</c>](#T%3aSystem.Nullable%601) to the [<c>Result\`1</c>](#T%3aMonacs.Core.Result%601) type.             If the value is null, the Error case is yielded.             Otherwise Ok case with provided value is returned.





##### Generic parameters
|Name|Description|
|---|---|
|T|Type of the encapsulated value.|

##### Parameters
|Name|Description|
|---|---|
|value|The value to convert to .|
|errorFunc|Function yielding details of the error if the value is null.|

#### Method <a name="M%3aMonacs.Core.Result.ToResult%60%601(System.Nullable%7b%60%600%7d%2cMonacs.Core.ErrorDetails)"><code>ToResult</code></a>
 Converts the value of [<c>System.Nullable\`1</c>](#T%3aSystem.Nullable%601) to the [<c>Result\`1</c>](#T%3aMonacs.Core.Result%601) type.             If the value is null, the Error case is yielded.             Otherwise Ok case with provided value is returned.

*Remarks:* Extension method variant of [<c>Result.OfNullable\`\`1(System.Nullable{\`\`0},ErrorDetails)</c>](#M%3aMonacs.Core.Result.OfNullable%60%601(System.Nullable%7b%60%600%7d%2cMonacs.Core.ErrorDetails))





##### Generic parameters
|Name|Description|
|---|---|
|T|Type of the encapsulated value.|

##### Parameters
|Name|Description|
|---|---|
|value|The value to convert to .|
|error|Details of the error if the value is null.|

#### Method <a name="M%3aMonacs.Core.Result.ToResult%60%601(System.Nullable%7b%60%600%7d%2cSystem.Func%7bMonacs.Core.ErrorDetails%7d)"><code>ToResult</code></a>
 Converts the value of [<c>System.Nullable\`1</c>](#T%3aSystem.Nullable%601) to the [<c>Result\`1</c>](#T%3aMonacs.Core.Result%601) type.             If the value is null, the Error case is yielded.             Otherwise Ok case with provided value is returned.

*Remarks:* Extension method variant of [<c>Result.OfNullable\`\`1(System.Nullable{\`\`0},System.Func{ErrorDetails})</c>](#M%3aMonacs.Core.Result.OfNullable%60%601(System.Nullable%7b%60%600%7d%2cSystem.Func%7bMonacs.Core.ErrorDetails%7d))





##### Generic parameters
|Name|Description|
|---|---|
|T|Type of the encapsulated value.|

##### Parameters
|Name|Description|
|---|---|
|value|The value to convert to .|
|errorFunc|Function yielding details of the error if the value is null.|

#### Method <a name="M%3aMonacs.Core.Result.OfString(System.String%2cMonacs.Core.ErrorDetails)"><code>OfString</code></a>
 Converts the string value to the [<c>Result\`1</c>](#T%3aMonacs.Core.Result%601) type.             If the value is null or empty string, the Error case is yielded.             Otherwise Ok case with provided value is returned.





##### Parameters
|Name|Description|
|---|---|
|value|The value to convert to .|
|error|Details of the error if the value is null or empty.|

#### Method <a name="M%3aMonacs.Core.Result.OfString(System.String%2cSystem.Func%7bMonacs.Core.ErrorDetails%7d)"><code>OfString</code></a>
 Converts the string value to the [<c>Result\`1</c>](#T%3aMonacs.Core.Result%601) type.             If the value is null or empty string, the Error case is yielded.             Otherwise Ok case with provided value is returned.





##### Parameters
|Name|Description|
|---|---|
|value|The value to convert to .|
|errorFunc|Function yielding details of the error if the value is null or empty.|

#### Method <a name="M%3aMonacs.Core.Result.ToResult(System.String%2cMonacs.Core.ErrorDetails)"><code>ToResult</code></a>
 Converts the string value to the [<c>Result\`1</c>](#T%3aMonacs.Core.Result%601) type.             If the value is null or empty string, the Error case is yielded.             Otherwise Ok case with provided value is returned.

*Remarks:* Extension method variant of [<c>Result.OfString(System.String,ErrorDetails)</c>](#M%3aMonacs.Core.Result.OfString(System.String%2cMonacs.Core.ErrorDetails))





##### Parameters
|Name|Description|
|---|---|
|value|The value to convert to .|
|error|Details of the error if the value is null or empty.|

#### Method <a name="M%3aMonacs.Core.Result.ToResult(System.String%2cSystem.Func%7bMonacs.Core.ErrorDetails%7d)"><code>ToResult</code></a>
 Converts the string value to the [<c>Result\`1</c>](#T%3aMonacs.Core.Result%601) type.             If the value is null or empty string, the Error case is yielded.             Otherwise Ok case with provided value is returned.

*Remarks:* Extension method variant of [<c>Result.OfString(System.String,System.Func{ErrorDetails})</c>](#M%3aMonacs.Core.Result.OfString(System.String%2cSystem.Func%7bMonacs.Core.ErrorDetails%7d))





##### Parameters
|Name|Description|
|---|---|
|value|The value to convert to .|
|errorFunc|Function yielding details of the error if the value is null or empty.|

#### Method <a name="M%3aMonacs.Core.Result.OfOption%60%601(Monacs.Core.Option%7b%60%600%7d%2cMonacs.Core.ErrorDetails)"><code>OfOption</code></a>
 Converts the value of [<c>Option\`1</c>](#T%3aMonacs.Core.Option%601) to the [<c>Result\`1</c>](#T%3aMonacs.Core.Result%601) type.             If the value is None case, the Error case is yielded.             Otherwise Ok case with provided value is returned.





##### Generic parameters
|Name|Description|
|---|---|
|T|Type of the encapsulated value.|

##### Parameters
|Name|Description|
|---|---|
|value|The value to convert to .|
|error|Details of the error if the value is None.|

#### Method <a name="M%3aMonacs.Core.Result.OfOption%60%601(Monacs.Core.Option%7b%60%600%7d%2cSystem.Func%7bMonacs.Core.ErrorDetails%7d)"><code>OfOption</code></a>
 Converts the value of [<c>Option\`1</c>](#T%3aMonacs.Core.Option%601) to the [<c>Result\`1</c>](#T%3aMonacs.Core.Result%601) type.             If the value is None case, the Error case is yielded.             Otherwise Ok case with provided value is returned.





##### Generic parameters
|Name|Description|
|---|---|
|T|Type of the encapsulated value.|

##### Parameters
|Name|Description|
|---|---|
|value|The value to convert to .|
|errorFunc|Function yielding details of the error if the value is None.|

#### Method <a name="M%3aMonacs.Core.Result.ToResult%60%601(Monacs.Core.Option%7b%60%600%7d%2cMonacs.Core.ErrorDetails)"><code>ToResult</code></a>
 Converts the value of [<c>Option\`1</c>](#T%3aMonacs.Core.Option%601) to the [<c>Result\`1</c>](#T%3aMonacs.Core.Result%601) type.             If the value is None case, the Error case is yielded.             Otherwise Ok case with provided value is returned.

*Remarks:* Extension method variant of [<c>Result.OfOption\`\`1(Option{\`\`0},ErrorDetails)</c>](#M%3aMonacs.Core.Result.OfOption%60%601(Monacs.Core.Option%7b%60%600%7d%2cMonacs.Core.ErrorDetails))





##### Generic parameters
|Name|Description|
|---|---|
|T|Type of the encapsulated value.|

##### Parameters
|Name|Description|
|---|---|
|value|The value to convert to .|
|error|Details of the error if the value is None.|

#### Method <a name="M%3aMonacs.Core.Result.ToResult%60%601(Monacs.Core.Option%7b%60%600%7d%2cSystem.Func%7bMonacs.Core.ErrorDetails%7d)"><code>ToResult</code></a>
 Converts the value of [<c>Option\`1</c>](#T%3aMonacs.Core.Option%601) to the [<c>Result\`1</c>](#T%3aMonacs.Core.Result%601) type.             If the value is None case, the Error case is yielded.             Otherwise Ok case with provided value is returned.

*Remarks:* Extension method variant of [<c>Result.OfOption\`\`1(Option{\`\`0},System.Func{ErrorDetails})</c>](#M%3aMonacs.Core.Result.OfOption%60%601(Monacs.Core.Option%7b%60%600%7d%2cSystem.Func%7bMonacs.Core.ErrorDetails%7d))





##### Generic parameters
|Name|Description|
|---|---|
|T|Type of the encapsulated value.|

##### Parameters
|Name|Description|
|---|---|
|value|The value to convert to .|
|errorFunc|Function yielding details of the error if the value is None.|

#### Method <a name="M%3aMonacs.Core.Result.TryGetResult%60%602(System.Collections.Generic.IDictionary%7b%60%600%2c%60%601%7d%2c%60%600%2cMonacs.Core.ErrorDetails)"><code>TryGetResult</code></a>
 Tries to get the element with the given [<c>key</c>](#key) from the [<c>dictionary</c>](#dictionary) .             If the value is found, returns Ok case of the [<c>Result\`1</c>](#T%3aMonacs.Core.Result%601) type with the value from the dictionary.             Otherwise returns Error case of the [<c>Result\`1</c>](#T%3aMonacs.Core.Result%601) type.







##### Generic parameters
|Name|Description|
|---|---|
|TKey|Type of the key in the dictionary.|
|TValue|Type of the value in the dictionary.|

##### Parameters
|Name|Description|
|---|---|
|dictionary|The dictionary to search in.|
|key|The key to look for.|
|error|Details of the error if the key is not found.|

#### Method <a name="M%3aMonacs.Core.Result.TryGetResult%60%602(System.Collections.Generic.IDictionary%7b%60%600%2c%60%601%7d%2c%60%600%2cSystem.Func%7b%60%600%2cMonacs.Core.ErrorDetails%7d)"><code>TryGetResult</code></a>
 Tries to get the element with the given [<c>key</c>](#key) from the [<c>dictionary</c>](#dictionary) .             If the value is found, returns Ok case of the [<c>Result\`1</c>](#T%3aMonacs.Core.Result%601) type with the value from the dictionary.             Otherwise returns Error case of the [<c>Result\`1</c>](#T%3aMonacs.Core.Result%601) type.







##### Generic parameters
|Name|Description|
|---|---|
|TKey|Type of the key in the dictionary.|
|TValue|Type of the value in the dictionary.|

##### Parameters
|Name|Description|
|---|---|
|dictionary|The dictionary to search in.|
|key|The key to look for.|
|errorFunc|Function yielding details of the error if the key is not found.|

#### Method <a name="M%3aMonacs.Core.Result.TryGetResult%60%602(System.Linq.ILookup%7b%60%600%2c%60%601%7d%2c%60%600%2cMonacs.Core.ErrorDetails)"><code>TryGetResult</code></a>
 Tries to get the elements with the given [<c>key</c>](#key) from the [<c>lookup</c>](#lookup) .             If any value is found, returns Ok case of the [<c>Result\`1</c>](#T%3aMonacs.Core.Result%601) type with the values from the lookup.             Otherwise returns Error case of the [<c>Result\`1</c>](#T%3aMonacs.Core.Result%601) type.







##### Generic parameters
|Name|Description|
|---|---|
|TKey|Type of the key in the lookup.|
|TValue|Type of the value in the lookup.|

##### Parameters
|Name|Description|
|---|---|
|lookup|The lookup to search in.|
|key|The key to look for.|
|error|Details of the error if the key is not found.|

#### Method <a name="M%3aMonacs.Core.Result.TryGetResult%60%602(System.Linq.ILookup%7b%60%600%2c%60%601%7d%2c%60%600%2cSystem.Func%7b%60%600%2cMonacs.Core.ErrorDetails%7d)"><code>TryGetResult</code></a>
 Tries to get the elements with the given [<c>key</c>](#key) from the [<c>lookup</c>](#lookup) .             If any value is found, returns Ok case of the [<c>Result\`1</c>](#T%3aMonacs.Core.Result%601) type with the values from the lookup.             Otherwise returns Error case of the [<c>Result\`1</c>](#T%3aMonacs.Core.Result%601) type.







##### Generic parameters
|Name|Description|
|---|---|
|TKey|Type of the key in the lookup.|
|TValue|Type of the value in the lookup.|

##### Parameters
|Name|Description|
|---|---|
|lookup|The lookup to search in.|
|key|The key to look for.|
|errorFunc|Function yielding details of the error if the key is not found.|

#### Method <a name="M%3aMonacs.Core.Result.Match%60%602(Monacs.Core.Result%7b%60%600%7d%2cSystem.Func%7b%60%600%2c%60%601%7d%2cSystem.Func%7bMonacs.Core.ErrorDetails%2c%60%601%7d)"><code>Match</code></a>
 Does the pattern matching on the [<c>Result\`1</c>](#T%3aMonacs.Core.Result%601) type.             If the [<c>result</c>](#result) is Ok, calls [<c>ok</c>](#ok) function             with the value from the result as a parameter and returns its result.             Otherwise calls [<c>error</c>](#error) function and returns its result.







##### Generic parameters
|Name|Description|
|---|---|
|TIn|Type of the value in the result.|
|TOut|Type of the returned value.|

##### Parameters
|Name|Description|
|---|---|
|result|The result to match on.|
|ok|Function called for the Ok case.|
|error|Function called for the Error case.|

#### Method <a name="M%3aMonacs.Core.Result.MatchTo%60%602(Monacs.Core.Result%7b%60%600%7d%2c%60%601%2c%60%601)"><code>MatchTo</code></a>
 Does the pattern matching on the [<c>Result\`1</c>](#T%3aMonacs.Core.Result%601) type.             If the [<c>result</c>](#result) is Ok, returns [<c>ok</c>](#ok) value.             Otherwise returns [<c>error</c>](#error) value.







##### Generic parameters
|Name|Description|
|---|---|
|TIn|Type of the value in the result.|
|TOut|Type of the returned value.|

##### Parameters
|Name|Description|
|---|---|
|result|The result to match on.|
|ok|Value returned for the Ok case.|
|error|Value returned for the Error case.|

#### Method <a name="M%3aMonacs.Core.Result.Bind%60%602(Monacs.Core.Result%7b%60%600%7d%2cSystem.Func%7b%60%600%2cMonacs.Core.Result%7b%60%601%7d%7d)"><code>Bind</code></a>
 Transforms the [<c>result</c>](#result) into another [<c>Result\`1</c>](#T%3aMonacs.Core.Result%601) using the [<c>binder</c>](#binder) function.             If the input result is Ok, returns the value of the binder call (which is [<c>Result\`1</c>](#T%3aMonacs.Core.Result%601) of [<c>TOut</c>](#TOut) ).             Otherwise returns Error case of the Result of [<c>TOut</c>](#TOut) .






##### Generic parameters
|Name|Description|
|---|---|
|TIn|Type of the value in the input result.|
|TOut|Type of the value in the returned result.|

##### Parameters
|Name|Description|
|---|---|
|result|The result to bind with.|
|binder|Function called with the input result value if it's Ok case.|

#### Method <a name="M%3aMonacs.Core.Result.Map%60%602(Monacs.Core.Result%7b%60%600%7d%2cSystem.Func%7b%60%600%2c%60%601%7d)"><code>Map</code></a>
 Maps the value of the [<c>result</c>](#result) into another [<c>Result\`1</c>](#T%3aMonacs.Core.Result%601) using the [<c>mapper</c>](#mapper) function.             If the input result is Ok, returns the Ok case with the value of the mapper call (which is [<c>TOut</c>](#TOut) ).             Otherwise returns Error case of the Result of [<c>TOut</c>](#TOut) .






##### Generic parameters
|Name|Description|
|---|---|
|TIn|Type of the value in the input result.|
|TOut|Type of the value in the returned result.|

##### Parameters
|Name|Description|
|---|---|
|result|The result to map on.|
|mapper|Function called with the input result value if it's Ok case.|

#### Method <a name="M%3aMonacs.Core.Result.GetOrDefault%60%601(Monacs.Core.Result%7b%60%600%7d%2c%60%600)"><code>GetOrDefault</code></a>
 Gets the value of the [<c>result</c>](#result) if it's Ok case.             If the result is Error case returns value specified by the [<c>whenError</c>](#whenError) parameter;             if the parameter is not set returns the default value of the type [<c>T</c>](#T) .





##### Generic parameters
|Name|Description|
|---|---|
|T|Type of the value in the result.|

##### Parameters
|Name|Description|
|---|---|
|result|The result to get a value from.|
|whenError|Value to return if the result is the Error case.|

#### Method <a name="M%3aMonacs.Core.Result.GetOrDefault%60%602(Monacs.Core.Result%7b%60%600%7d%2cSystem.Func%7b%60%600%2c%60%601%7d%2c%60%601)"><code>GetOrDefault</code></a>
 Gets the value from the [<c>result</c>](#result) using the [<c>getter</c>](#getter) function if it's Ok case.             If the result is Error case returns value specified by the [<c>whenError</c>](#whenError) parameter;             if the parameter is not set returns the default value of the type [<c>TOut</c>](#TOut) .

*Remarks:* Effectively the combination of [<c>Result.Map\`\`2(Result{\`\`0},System.Func{\`\`0,\`\`1})</c>](#M%3aMonacs.Core.Result.Map%60%602(Monacs.Core.Result%7b%60%600%7d%2cSystem.Func%7b%60%600%2c%60%601%7d)) and [<c>Result.GetOrDefault\`\`1(Result{\`\`0},\`\`0)</c>](#M%3aMonacs.Core.Result.GetOrDefault%60%601(Monacs.Core.Result%7b%60%600%7d%2c%60%600)) calls.







##### Generic parameters
|Name|Description|
|---|---|
|TIn|Type of the value in the result.|
|TOut|Type of the return value.|

##### Parameters
|Name|Description|
|---|---|
|result|The result to get a value from.|
|getter|Function used to get the value if the result is the Ok case.|
|whenError|Value to return if the result is the Error case.|

#### Method <a name="M%3aMonacs.Core.Result.Do%60%601(Monacs.Core.Result%7b%60%600%7d%2cSystem.Action%7b%60%600%7d)"><code>Do</code></a>
 Performs the [<c>action</c>](#action) with the value of the [<c>result</c>](#result) if it's Ok case.             If the result is Error case nothing happens.             In both cases unmodified result is returned.





##### Generic parameters
|Name|Description|
|---|---|
|T|Type of the value in the result.|

##### Parameters
|Name|Description|
|---|---|
|result|The result to check for a value.|
|action|Function executed if the result is Ok case.|

#### Method <a name="M%3aMonacs.Core.Result.DoWhenError%60%601(Monacs.Core.Result%7b%60%600%7d%2cSystem.Action%7bMonacs.Core.ErrorDetails%7d)"><code>DoWhenError</code></a>
 Performs the [<c>action</c>](#action) if the [<c>result</c>](#result) is Error case.             If the result is Ok case nothing happens.             In both cases unmodified result is returned.





##### Generic parameters
|Name|Description|
|---|---|
|T|Type of the value in the result.|

##### Parameters
|Name|Description|
|---|---|
|result|The result to check for a value.|
|action|Function executed if the result is Error case.|

#### Method <a name="M%3aMonacs.Core.Result.Choose%60%601(System.Collections.Generic.IEnumerable%7bMonacs.Core.Result%7b%60%600%7d%7d)"><code>Choose</code></a>
 Returns the collection of values of elements from the [<c>Result\`1</c>](#T%3aMonacs.Core.Result%601) collection             that are Ok case.




##### Generic parameters
|Name|Description|
|---|---|
|T|Type of the value in the result.|

##### Parameters
|Name|Description|
|---|---|
|items|Collection to filter out and map.|

#### Method <a name="M%3aMonacs.Core.Result.ChooseErrors%60%601(System.Collections.Generic.IEnumerable%7bMonacs.Core.Result%7b%60%600%7d%7d)"><code>ChooseErrors</code></a>
 Returns the collection of values of elements from the [<c>Result\`1</c>](#T%3aMonacs.Core.Result%601) collection             that are Error case.




##### Generic parameters
|Name|Description|
|---|---|
|T|Type of the value in the result.|

##### Parameters
|Name|Description|
|---|---|
|items|Collection to filter out and map.|

#### Method <a name="M%3aMonacs.Core.Result.Sequence%60%601(System.Collections.Generic.IEnumerable%7bMonacs.Core.Result%7b%60%600%7d%7d)"><code>Sequence</code></a>
 If all elements in the input collection are Ok case, returns the Ok of the collection of underlying values.             Otherwise returns Error from the first element.




##### Generic parameters
|Name|Description|
|---|---|
|T|Type of the value in the result.|

##### Parameters
|Name|Description|
|---|---|
|items|Collection to check and map.|

#### Method <a name="M%3aMonacs.Core.Result.TryCatch%60%601(System.Func%7b%60%600%7d%2cSystem.Func%7bSystem.Exception%2cMonacs.Core.ErrorDetails%7d)"><code>TryCatch</code></a>
 Tries to execute [<c>func</c>](#func) .             If the execution completes without exception, returns Ok with the function result.             Otherwise returns Error with details generated by [<c>errorHandler</c>](#errorHandler) based on the thrown exception.





##### Generic parameters
|Name|Description|
|---|---|
|T|Type of the value in the result.|

##### Parameters
|Name|Description|
|---|---|
|func|Function to execute.|
|errorHandler|Function that generates error details in case of exception.|

#### Method <a name="M%3aMonacs.Core.Result.TryCatch%60%602(Monacs.Core.Result%7b%60%600%7d%2cSystem.Func%7b%60%600%2c%60%601%7d%2cSystem.Func%7b%60%600%2cSystem.Exception%2cMonacs.Core.ErrorDetails%7d)"><code>TryCatch</code></a>
 Tries to execute [<c>func</c>](#func) with the value from the [<c>result</c>](#result) as an input.             If the execution completes without exception, returns Ok with the function result.             Otherwise returns Error with details generated by [<c>errorHandler</c>](#errorHandler) based on the thrown exception.             If the [<c>result</c>](#result) is Error function is not executed and the Error is returned.







##### Generic parameters
|Name|Description|
|---|---|
|TIn|Type of the value in the input result.|
|TOut|Type of the value in the output result.|

##### Parameters
|Name|Description|
|---|---|
|result|Result to take the value from.|
|func|Function to execute.|
|errorHandler|Function that generates error details in case of exception.|


## Type <a name="T%3aMonacs.Core.Unit.Result"><code>Monacs.Core.Unit.Result</code></a>
 Contains the set of extensions to work with the [<c>Result\`1</c>](#T%3aMonacs.Core.Result%601) type.


### Methods
#### Method <a name="M%3aMonacs.Core.Unit.Result.Ok"><code>Ok</code></a>
 Creates the Ok case instance of the [<c>Result\`1</c>](#T%3aMonacs.Core.Result%601) .




#### Method <a name="M%3aMonacs.Core.Unit.Result.Error(Monacs.Core.ErrorDetails)"><code>Error</code></a>
 Creates the Error case instance of the [<c>Result\`1</c>](#T%3aMonacs.Core.Result%601) type, containing error instead of value.




##### Parameters
|Name|Description|
|---|---|
|error|Details of the error.|

#### Method <a name="M%3aMonacs.Core.Unit.Result.Ignore%60%601(Monacs.Core.Result%7b%60%600%7d)"><code>Ignore</code></a>
 Rejects the value of the [<c>Result\`1</c>](#T%3aMonacs.Core.Result%601) and returns [<c>Result\`1</c>](#T%3aMonacs.Core.Result%601) instead.              If the input [<c>Result\`1</c>](#T%3aMonacs.Core.Result%601) is Error then the error details are preserved.




##### Generic parameters
|Name|Description|
|---|---|
|T|Type of the encapsulated value.|

##### Parameters
|Name|Description|
|---|---|
|result|The result of which the value should be ignored.|


## Type <a name="T%3aMonacs.Core.Unit.Unit"><code>Monacs.Core.Unit.Unit</code></a>
 Type that has only one value.              Used to replace void whenever some value is needed, e.g. you can return Task{Unit}.


### Methods
#### Method <a name="M%3aMonacs.Core.Unit.Unit.Equals(Monacs.Core.Unit.Unit)"><code>Equals</code></a>
 [<c>Unit.Unit</c>](#T%3aMonacs.Core.Unit.Unit) is always equal to itself. There is only one possible value of [<c>Unit.Unit</c>](#T%3aMonacs.Core.Unit.Unit) .




#### Method <a name="M%3aMonacs.Core.Unit.Unit.Equals(System.Object)"><code>Equals</code></a>
 [<c>Unit.Unit</c>](#T%3aMonacs.Core.Unit.Unit) is only equal to itself.




#### Method <a name="M%3aMonacs.Core.Unit.Unit.GetHashCode"><code>GetHashCode</code></a>
 Hash Code of [<c>Unit.Unit</c>](#T%3aMonacs.Core.Unit.Unit) is always 0.




#### Method <a name="M%3aMonacs.Core.Unit.Unit.ToString"><code>ToString</code></a>
 String representation of [<c>Unit.Unit</c>](#T%3aMonacs.Core.Unit.Unit) is ().




#### Method <a name="M%3aMonacs.Core.Unit.Unit.op_Equality(Monacs.Core.Unit.Unit%2cMonacs.Core.Unit.Unit)"><code>op_Equality</code></a>
 [<c>Unit.Unit</c>](#T%3aMonacs.Core.Unit.Unit) is always equal to itself.




#### Method <a name="M%3aMonacs.Core.Unit.Unit.op_Inequality(Monacs.Core.Unit.Unit%2cMonacs.Core.Unit.Unit)"><code>op_Inequality</code></a>
 [<c>Unit.Unit</c>](#T%3aMonacs.Core.Unit.Unit) is always equal to itself.





### Properties
#### Property <a name="P%3aMonacs.Core.Unit.Unit.Default"><code>Default</code></a>
 The only value of [<c>Unit.Unit</c>](#T%3aMonacs.Core.Unit.Unit) .



