<a id="Monacs.Core.ErrorLevel"></a>
## ErrorLevel
*enum Monacs.Core.ErrorLevel*

Represents the severity of the error.

**Enum Values**

* **Trace**
* **Debug**
* **Info**
* **Warn**
* **Error**
* **Fatal**


---

<a id="Monacs.Core.Errors"></a>
## Errors
*class Monacs.Core.Errors*

Contains factory methods to create instances of [Monacs.Core.ErrorDetails](#Monacs.Core.ErrorDetails) in a more convenient way.

**Static Methods**

<a id="Monacs.Core.Errors.Trace(System.String,System.String,System.Exception,System.Object)"></a>

* *ErrorDetails* **Trace** *([String message], [String key], [Exception exception], [Object metadata])*  
  Creates [Monacs.Core.ErrorDetails](#Monacs.Core.ErrorDetails) with level [Monacs.Core.ErrorLevel.Trace](#Monacs.Core.ErrorLevel.Trace) .  

<a id="Monacs.Core.Errors.Debug(System.String,System.String,System.Exception,System.Object)"></a>

* *ErrorDetails* **Debug** *([String message], [String key], [Exception exception], [Object metadata])*  
  Creates [Monacs.Core.ErrorDetails](#Monacs.Core.ErrorDetails) with level [Monacs.Core.ErrorLevel.Debug](#Monacs.Core.ErrorLevel.Debug) .  

<a id="Monacs.Core.Errors.Info(System.String,System.String,System.Exception,System.Object)"></a>

* *ErrorDetails* **Info** *([String message], [String key], [Exception exception], [Object metadata])*  
  Creates [Monacs.Core.ErrorDetails](#Monacs.Core.ErrorDetails) with level [Monacs.Core.ErrorLevel.Info](#Monacs.Core.ErrorLevel.Info) .  

<a id="Monacs.Core.Errors.Warn(System.String,System.String,System.Exception,System.Object)"></a>

* *ErrorDetails* **Warn** *([String message], [String key], [Exception exception], [Object metadata])*  
  Creates [Monacs.Core.ErrorDetails](#Monacs.Core.ErrorDetails) with level [Monacs.Core.ErrorLevel.Warn](#Monacs.Core.ErrorLevel.Warn) .  

<a id="Monacs.Core.Errors.Error(System.String,System.String,System.Exception,System.Object)"></a>

* *ErrorDetails* **Error** *([String message], [String key], [Exception exception], [Object metadata])*  
  Creates [Monacs.Core.ErrorDetails](#Monacs.Core.ErrorDetails) with level [Monacs.Core.ErrorLevel.Error](#Monacs.Core.ErrorLevel.Error) .  

<a id="Monacs.Core.Errors.Fatal(System.String,System.String,System.Exception,System.Object)"></a>

* *ErrorDetails* **Fatal** *([String message], [String key], [Exception exception], [Object metadata])*  
  Creates [Monacs.Core.ErrorDetails](#Monacs.Core.ErrorDetails) with level [Monacs.Core.ErrorLevel.Fatal](#Monacs.Core.ErrorLevel.Fatal) .  




---

<a id="Monacs.Core.Option"></a>
## Option
*class Monacs.Core.Option*

Contains the set of extensions to work with the [Monacs.Core.Option`1](#Monacs.Core.Option`1) type.

**Static Methods**

<a id="Monacs.Core.Option.Some()"></a>

* *Option&lt;T&gt;* **Some** *(T value)*  

<a id="Monacs.Core.Option.None"></a>

* *Option&lt;T&gt;* **None** *()*  

<a id="Monacs.Core.Option.OfObject()"></a>

* *Option&lt;T&gt;* **OfObject** *(T value)*  

<a id="Monacs.Core.Option.ToOption()"></a>

* *Option&lt;T&gt;* **ToOption** *(T value)*  

<a id="Monacs.Core.Option.OfNullable()"></a>

* *Option&lt;T&gt;* **OfNullable** *(Nullable&lt;T&gt; value)*  

<a id="Monacs.Core.Option.ToOption()"></a>

* *Option&lt;T&gt;* **ToOption** *(Nullable&lt;T&gt; value)*  

<a id="Monacs.Core.Option.ToNullable()"></a>

* *Nullable&lt;T&gt;* **ToNullable** *(Option&lt;T&gt; value)*  

<a id="Monacs.Core.Option.OfString(System.String)"></a>

* *Option&lt;String&gt;* **OfString** *(String value)*  
  Converts the string value to the [Monacs.Core.Option`1](#Monacs.Core.Option`1) type.
If the value is null or empty string, the None case is yielded.
Otherwise Some case with provided value is returned.  

<a id="Monacs.Core.Option.ToOption(System.String)"></a>

* *Option&lt;String&gt;* **ToOption** *(String value)*  
  Converts the string value to the [Option{string}](#Option{string}) type.
If the value is null or empty string, the None case is yielded.
Otherwise Some case with provided value is returned.  
  Extension method variant of [Monacs.Core.Option.OfString(System.String)](#Monacs.Core.Option.OfString(System.String)) 

<a id="Monacs.Core.Option.OfResult()"></a>

* *Option&lt;T&gt;* **OfResult** *(Result&lt;T&gt; value)*  

<a id="Monacs.Core.Option.ToOption()"></a>

* *Option&lt;T&gt;* **ToOption** *(Result&lt;T&gt; value)*  

<a id="Monacs.Core.Option.TryGetOption(,)"></a>

* *Option&lt;TValue&gt;* **TryGetOption** *(IDictionary&lt;TKey, TValue&gt; dictionary, TKey key)*  

<a id="Monacs.Core.Option.TryGetOption(,)"></a>

* *Option&lt;IEnumerable&lt;TValue&gt;&gt;* **TryGetOption** *(ILookup&lt;TKey, TValue&gt; lookup, TKey key)*  

<a id="Monacs.Core.Option.Match(,,)"></a>

* *TOut* **Match** *(Option&lt;TIn&gt; option, Func&lt;TIn, TOut&gt; some, Func&lt;TOut&gt; none)*  

<a id="Monacs.Core.Option.MatchTo(,,)"></a>

* *TOut* **MatchTo** *(Option&lt;TIn&gt; option, TOut some, TOut none)*  

<a id="Monacs.Core.Option.Bind(,)"></a>

* *Option&lt;TOut&gt;* **Bind** *(Option&lt;TIn&gt; option, Func&lt;TIn, Option&lt;TOut&gt;&gt; binder)*  

<a id="Monacs.Core.Option.Map(,)"></a>

* *Option&lt;TOut&gt;* **Map** *(Option&lt;TIn&gt; option, Func&lt;TIn, TOut&gt; mapper)*  

<a id="Monacs.Core.Option.GetOrDefault(,)"></a>

* *T* **GetOrDefault** *(Option&lt;T&gt; option, [T whenNone])*  

<a id="Monacs.Core.Option.GetOrDefault(,,)"></a>

* *TOut* **GetOrDefault** *(Option&lt;TIn&gt; option, Func&lt;TIn, TOut&gt; getter, [TOut whenNone])*  

<a id="Monacs.Core.Option.Do(,)"></a>

* *Option&lt;T&gt;* **Do** *(Option&lt;T&gt; option, Action&lt;T&gt; action)*  

<a id="Monacs.Core.Option.DoWhenNone(,System.Action)"></a>

* *Option&lt;T&gt;* **DoWhenNone** *(Option&lt;T&gt; option, Action action)*  

<a id="Monacs.Core.Option.Choose()"></a>

* *IEnumerable&lt;T&gt;* **Choose** *(IEnumerable&lt;Option&lt;T&gt;&gt; items)*  

<a id="Monacs.Core.Option.Sequence()"></a>

* *Option&lt;IEnumerable&lt;T&gt;&gt;* **Sequence** *(IEnumerable&lt;Option&lt;T&gt;&gt; items)*  

<a id="Monacs.Core.Option.TryFind(,)"></a>

* *Option&lt;T&gt;* **TryFind** *(IEnumerable&lt;T&gt; items, Func&lt;T, Boolean&gt; predicate)*  

<a id="Monacs.Core.Option.TryFirst()"></a>

* *Option&lt;T&gt;* **TryFirst** *(IEnumerable&lt;T&gt; items)*  

<a id="Monacs.Core.Option.TryElementAt(,System.Int32)"></a>

* *Option&lt;T&gt;* **TryElementAt** *(IEnumerable&lt;T&gt; items, Int32 index)*  




---

<a id="Monacs.Core.Result"></a>
## Result
*class Monacs.Core.Result*

Contains the set of extensions to work with the [Monacs.Core.Result`1](#Monacs.Core.Result`1) type.

**Static Methods**

<a id="Monacs.Core.Result.Ok()"></a>

* *Result&lt;T&gt;* **Ok** *(T value)*  

<a id="Monacs.Core.Result.Error(Monacs.Core.ErrorDetails)"></a>

* *Result&lt;T&gt;* **Error** *(ErrorDetails error)*  

<a id="Monacs.Core.Result.OfObject(,Monacs.Core.ErrorDetails)"></a>

* *Result&lt;T&gt;* **OfObject** *(T value, ErrorDetails error)*  

<a id="Monacs.Core.Result.OfObject(,System.Func`1[[Monacs.Core.ErrorDetails, Monacs.Core, Version=1.0.0.0, Culture=neutral, PublicKeyToken=null]])"></a>

* *Result&lt;T&gt;* **OfObject** *(T value, Func&lt;ErrorDetails&gt; errorFunc)*  

<a id="Monacs.Core.Result.ToResult(,Monacs.Core.ErrorDetails)"></a>

* *Result&lt;T&gt;* **ToResult** *(T value, ErrorDetails error)*  

<a id="Monacs.Core.Result.ToResult(,System.Func`1[[Monacs.Core.ErrorDetails, Monacs.Core, Version=1.0.0.0, Culture=neutral, PublicKeyToken=null]])"></a>

* *Result&lt;T&gt;* **ToResult** *(T value, Func&lt;ErrorDetails&gt; errorFunc)*  

<a id="Monacs.Core.Result.OfNullable(,Monacs.Core.ErrorDetails)"></a>

* *Result&lt;T&gt;* **OfNullable** *(Nullable&lt;T&gt; value, ErrorDetails error)*  

<a id="Monacs.Core.Result.OfNullable(,System.Func`1[[Monacs.Core.ErrorDetails, Monacs.Core, Version=1.0.0.0, Culture=neutral, PublicKeyToken=null]])"></a>

* *Result&lt;T&gt;* **OfNullable** *(Nullable&lt;T&gt; value, Func&lt;ErrorDetails&gt; errorFunc)*  

<a id="Monacs.Core.Result.ToResult(,Monacs.Core.ErrorDetails)"></a>

* *Result&lt;T&gt;* **ToResult** *(Nullable&lt;T&gt; value, ErrorDetails error)*  

<a id="Monacs.Core.Result.ToResult(,System.Func`1[[Monacs.Core.ErrorDetails, Monacs.Core, Version=1.0.0.0, Culture=neutral, PublicKeyToken=null]])"></a>

* *Result&lt;T&gt;* **ToResult** *(Nullable&lt;T&gt; value, Func&lt;ErrorDetails&gt; errorFunc)*  

<a id="Monacs.Core.Result.OfString(System.String,Monacs.Core.ErrorDetails)"></a>

* *Result&lt;String&gt;* **OfString** *(String value, ErrorDetails error)*  
  Converts the string value to the [Monacs.Core.Result`1](#Monacs.Core.Result`1) type.
If the value is null or empty string, the Error case is yielded.
Otherwise Ok case with provided value is returned.  

<a id="Monacs.Core.Result.OfString(System.String,System.Func`1[[Monacs.Core.ErrorDetails, Monacs.Core, Version=1.0.0.0, Culture=neutral, PublicKeyToken=null]])"></a>

* *Result&lt;String&gt;* **OfString** *(String value, Func&lt;ErrorDetails&gt; errorFunc)*  

<a id="Monacs.Core.Result.ToResult(System.String,Monacs.Core.ErrorDetails)"></a>

* *Result&lt;String&gt;* **ToResult** *(String value, ErrorDetails error)*  
  Converts the string value to the [Monacs.Core.Result`1](#Monacs.Core.Result`1) type.
If the value is null or empty string, the Error case is yielded.
Otherwise Ok case with provided value is returned.  
  Extension method variant of [Monacs.Core.Result.OfString(System.String,Monacs.Core.ErrorDetails)](#Monacs.Core.Result.OfString(System.String,Monacs.Core.ErrorDetails)) 

<a id="Monacs.Core.Result.ToResult(System.String,System.Func`1[[Monacs.Core.ErrorDetails, Monacs.Core, Version=1.0.0.0, Culture=neutral, PublicKeyToken=null]])"></a>

* *Result&lt;String&gt;* **ToResult** *(String value, Func&lt;ErrorDetails&gt; errorFunc)*  

<a id="Monacs.Core.Result.OfOption(,Monacs.Core.ErrorDetails)"></a>

* *Result&lt;T&gt;* **OfOption** *(Option&lt;T&gt; value, ErrorDetails error)*  

<a id="Monacs.Core.Result.OfOption(,System.Func`1[[Monacs.Core.ErrorDetails, Monacs.Core, Version=1.0.0.0, Culture=neutral, PublicKeyToken=null]])"></a>

* *Result&lt;T&gt;* **OfOption** *(Option&lt;T&gt; value, Func&lt;ErrorDetails&gt; errorFunc)*  

<a id="Monacs.Core.Result.ToResult(,Monacs.Core.ErrorDetails)"></a>

* *Result&lt;T&gt;* **ToResult** *(Option&lt;T&gt; value, ErrorDetails error)*  

<a id="Monacs.Core.Result.ToResult(,System.Func`1[[Monacs.Core.ErrorDetails, Monacs.Core, Version=1.0.0.0, Culture=neutral, PublicKeyToken=null]])"></a>

* *Result&lt;T&gt;* **ToResult** *(Option&lt;T&gt; value, Func&lt;ErrorDetails&gt; errorFunc)*  

<a id="Monacs.Core.Result.TryGetResult(,,Monacs.Core.ErrorDetails)"></a>

* *Result&lt;TValue&gt;* **TryGetResult** *(IDictionary&lt;TKey, TValue&gt; dictionary, TKey key, ErrorDetails error)*  

<a id="Monacs.Core.Result.TryGetResult(,,)"></a>

* *Result&lt;TValue&gt;* **TryGetResult** *(IDictionary&lt;TKey, TValue&gt; dictionary, TKey key, Func&lt;TKey, ErrorDetails&gt; errorFunc)*  

<a id="Monacs.Core.Result.TryGetResult(,,Monacs.Core.ErrorDetails)"></a>

* *Result&lt;IEnumerable&lt;TValue&gt;&gt;* **TryGetResult** *(ILookup&lt;TKey, TValue&gt; lookup, TKey key, ErrorDetails error)*  

<a id="Monacs.Core.Result.TryGetResult(,,)"></a>

* *Result&lt;IEnumerable&lt;TValue&gt;&gt;* **TryGetResult** *(ILookup&lt;TKey, TValue&gt; lookup, TKey key, Func&lt;TKey, ErrorDetails&gt; errorFunc)*  

<a id="Monacs.Core.Result.Match(,,)"></a>

* *TOut* **Match** *(Result&lt;TIn&gt; result, Func&lt;TIn, TOut&gt; ok, Func&lt;ErrorDetails, TOut&gt; error)*  

<a id="Monacs.Core.Result.MatchTo(,,)"></a>

* *TOut* **MatchTo** *(Result&lt;TIn&gt; result, TOut ok, TOut error)*  

<a id="Monacs.Core.Result.Bind(,)"></a>

* *Result&lt;TOut&gt;* **Bind** *(Result&lt;TIn&gt; result, Func&lt;TIn, Result&lt;TOut&gt;&gt; binder)*  

<a id="Monacs.Core.Result.Map(,)"></a>

* *Result&lt;TOut&gt;* **Map** *(Result&lt;TIn&gt; result, Func&lt;TIn, TOut&gt; mapper)*  

<a id="Monacs.Core.Result.GetOrDefault(,)"></a>

* *T* **GetOrDefault** *(Result&lt;T&gt; result, [T whenError])*  

<a id="Monacs.Core.Result.GetOrDefault(,,)"></a>

* *TOut* **GetOrDefault** *(Result&lt;TIn&gt; result, Func&lt;TIn, TOut&gt; getter, [TOut whenError])*  

<a id="Monacs.Core.Result.Do(,)"></a>

* *Result&lt;T&gt;* **Do** *(Result&lt;T&gt; result, Action&lt;T&gt; action)*  

<a id="Monacs.Core.Result.DoWhenError(,System.Action`1[[Monacs.Core.ErrorDetails, Monacs.Core, Version=1.0.0.0, Culture=neutral, PublicKeyToken=null]])"></a>

* *Result&lt;T&gt;* **DoWhenError** *(Result&lt;T&gt; result, Action&lt;ErrorDetails&gt; action)*  

<a id="Monacs.Core.Result.Choose()"></a>

* *IEnumerable&lt;T&gt;* **Choose** *(IEnumerable&lt;Result&lt;T&gt;&gt; items)*  

<a id="Monacs.Core.Result.ChooseErrors()"></a>

* *IEnumerable&lt;ErrorDetails&gt;* **ChooseErrors** *(IEnumerable&lt;Result&lt;T&gt;&gt; items)*  

<a id="Monacs.Core.Result.Sequence()"></a>

* *Result&lt;IEnumerable&lt;T&gt;&gt;* **Sequence** *(IEnumerable&lt;Result&lt;T&gt;&gt; items)*  

<a id="Monacs.Core.Result.TryCatch(,System.Func`2[[System.Exception, mscorlib, Version=4.0.0.0, Culture=neutral, PublicKeyToken=b77a5c561934e089],[Monacs.Core.ErrorDetails, Monacs.Core, Version=1.0.0.0, Culture=neutral, PublicKeyToken=null]])"></a>

* *Result&lt;T&gt;* **TryCatch** *(Func&lt;T&gt; func, Func&lt;Exception, ErrorDetails&gt; errorHandler)*  

<a id="Monacs.Core.Result.TryCatch(,,)"></a>

* *Result&lt;TOut&gt;* **TryCatch** *(Result&lt;TIn&gt; result, Func&lt;TIn, TOut&gt; func, Func&lt;TIn, Exception, ErrorDetails&gt; errorHandler)*  




---

<a id="Monacs.Core.Unit.Result"></a>
## Result
*class Monacs.Core.Unit.Result*

Contains the set of extensions to work with the [Monacs.Core.Result`1](#Monacs.Core.Result`1) type.

**Static Methods**

<a id="Monacs.Core.Unit.Result.Ok"></a>

* *Result&lt;Unit&gt;* **Ok** *()*  
  Creates the Ok case instance of the [Monacs.Core.Result`1](#Monacs.Core.Result`1) .  

<a id="Monacs.Core.Unit.Result.Error(Monacs.Core.ErrorDetails)"></a>

* *Result&lt;Unit&gt;* **Error** *(ErrorDetails error)*  
  Creates the Error case instance of the [Monacs.Core.Result`1](#Monacs.Core.Result`1) type, containing error instead of value.  

<a id="Monacs.Core.Unit.Result.Ignore()"></a>

* *Result&lt;Unit&gt;* **Ignore** *(Result&lt;T&gt; result)*  




---

<a id="Monacs.Core.Async.Result"></a>
## Result
*class Monacs.Core.Async.Result*

Contains the set of async extensions to work with the [Monacs.Core.Result`1](#Monacs.Core.Result`1) type.

**Static Methods**

<a id="Monacs.Core.Async.Result.BindAsync(,)"></a>

* *Task&lt;Result&lt;TOut&gt;&gt;* **BindAsync** *(Result&lt;TIn&gt; result, Func&lt;TIn, Task&lt;Result&lt;TOut&gt;&gt;&gt; binder)*  

<a id="Monacs.Core.Async.Result.BindAsync(,)"></a>

* *Task&lt;Result&lt;TOut&gt;&gt;* **BindAsync** *(Task&lt;Result&lt;TIn&gt;&gt; result, Func&lt;TIn, Task&lt;Result&lt;TOut&gt;&gt;&gt; binder)*  

<a id="Monacs.Core.Async.Result.BindAsync(,)"></a>

* *Task&lt;Result&lt;TOut&gt;&gt;* **BindAsync** *(Task&lt;Result&lt;TIn&gt;&gt; result, Func&lt;TIn, Result&lt;TOut&gt;&gt; binder)*  

<a id="Monacs.Core.Async.Result.MapAsync(,)"></a>

* *Task&lt;Result&lt;TOut&gt;&gt;* **MapAsync** *(Result&lt;TIn&gt; result, Func&lt;TIn, Task&lt;TOut&gt;&gt; mapper)*  

<a id="Monacs.Core.Async.Result.MapAsync(,)"></a>

* *Task&lt;Result&lt;TOut&gt;&gt;* **MapAsync** *(Task&lt;Result&lt;TIn&gt;&gt; result, Func&lt;TIn, Task&lt;TOut&gt;&gt; mapper)*  

<a id="Monacs.Core.Async.Result.MapAsync(,)"></a>

* *Task&lt;Result&lt;TOut&gt;&gt;* **MapAsync** *(Task&lt;Result&lt;TIn&gt;&gt; result, Func&lt;TIn, TOut&gt; mapper)*  

<a id="Monacs.Core.Async.Result.MatchAsync(,,)"></a>

* *Task&lt;TOut&gt;* **MatchAsync** *(Result&lt;TIn&gt; result, Func&lt;TIn, Task&lt;TOut&gt;&gt; ok, Func&lt;ErrorDetails, Task&lt;TOut&gt;&gt; error)*  

<a id="Monacs.Core.Async.Result.MatchAsync(,,)"></a>

* *Task&lt;TOut&gt;* **MatchAsync** *(Result&lt;TIn&gt; result, Func&lt;TIn, Task&lt;TOut&gt;&gt; ok, Func&lt;ErrorDetails, TOut&gt; error)*  

<a id="Monacs.Core.Async.Result.MatchAsync(,,)"></a>

* *Task&lt;TOut&gt;* **MatchAsync** *(Result&lt;TIn&gt; result, Func&lt;TIn, TOut&gt; ok, Func&lt;ErrorDetails, Task&lt;TOut&gt;&gt; error)*  

<a id="Monacs.Core.Async.Result.MatchAsync(,,)"></a>

* *Task&lt;TOut&gt;* **MatchAsync** *(Task&lt;Result&lt;TIn&gt;&gt; result, Func&lt;TIn, TOut&gt; ok, Func&lt;ErrorDetails, TOut&gt; error)*  

<a id="Monacs.Core.Async.Result.MatchAsync(,,)"></a>

* *Task&lt;TOut&gt;* **MatchAsync** *(Task&lt;Result&lt;TIn&gt;&gt; result, Func&lt;TIn, Task&lt;TOut&gt;&gt; ok, Func&lt;ErrorDetails, Task&lt;TOut&gt;&gt; error)*  

<a id="Monacs.Core.Async.Result.MatchAsync(,,)"></a>

* *Task&lt;TOut&gt;* **MatchAsync** *(Task&lt;Result&lt;TIn&gt;&gt; result, Func&lt;TIn, Task&lt;TOut&gt;&gt; ok, Func&lt;ErrorDetails, TOut&gt; error)*  

<a id="Monacs.Core.Async.Result.MatchAsync(,,)"></a>

* *Task&lt;TOut&gt;* **MatchAsync** *(Task&lt;Result&lt;TIn&gt;&gt; result, Func&lt;TIn, TOut&gt; ok, Func&lt;ErrorDetails, Task&lt;TOut&gt;&gt; error)*  

<a id="Monacs.Core.Async.Result.IgnoreAsync()"></a>

* *Task&lt;Result&lt;Unit&gt;&gt;* **IgnoreAsync** *(Task&lt;Result&lt;T&gt;&gt; result)*  

<a id="Monacs.Core.Async.Result.DoAsync(,)"></a>

* *Task&lt;Result&lt;T&gt;&gt;* **DoAsync** *(Task&lt;Result&lt;T&gt;&gt; result, Action&lt;T&gt; action)*  

<a id="Monacs.Core.Async.Result.DoAsync(,)"></a>

* *Task&lt;Result&lt;T&gt;&gt;* **DoAsync** *(Result&lt;T&gt; result, Func&lt;T, Task&gt; action)*  

<a id="Monacs.Core.Async.Result.DoAsync(,)"></a>

* *Task&lt;Result&lt;T&gt;&gt;* **DoAsync** *(Task&lt;Result&lt;T&gt;&gt; result, Func&lt;T, Task&gt; action)*  

<a id="Monacs.Core.Async.Result.DoWhenErrorAsync(,System.Action`1[[Monacs.Core.ErrorDetails, Monacs.Core, Version=1.0.0.0, Culture=neutral, PublicKeyToken=null]])"></a>

* *Task&lt;Result&lt;T&gt;&gt;* **DoWhenErrorAsync** *(Task&lt;Result&lt;T&gt;&gt; result, Action&lt;ErrorDetails&gt; action)*  

<a id="Monacs.Core.Async.Result.DoWhenErrorAsync(,System.Func`2[[Monacs.Core.ErrorDetails, Monacs.Core, Version=1.0.0.0, Culture=neutral, PublicKeyToken=null],[System.Threading.Tasks.Task, mscorlib, Version=4.0.0.0, Culture=neutral, PublicKeyToken=b77a5c561934e089]])"></a>

* *Task&lt;Result&lt;T&gt;&gt;* **DoWhenErrorAsync** *(Result&lt;T&gt; result, Func&lt;ErrorDetails, Task&gt; action)*  

<a id="Monacs.Core.Async.Result.DoWhenErrorAsync(,System.Func`2[[Monacs.Core.ErrorDetails, Monacs.Core, Version=1.0.0.0, Culture=neutral, PublicKeyToken=null],[System.Threading.Tasks.Task, mscorlib, Version=4.0.0.0, Culture=neutral, PublicKeyToken=b77a5c561934e089]])"></a>

* *Task&lt;Result&lt;T&gt;&gt;* **DoWhenErrorAsync** *(Task&lt;Result&lt;T&gt;&gt; result, Func&lt;ErrorDetails, Task&gt; action)*  

<a id="Monacs.Core.Async.Result.FlipAsync()"></a>

* *Task&lt;Result&lt;T&gt;&gt;* **FlipAsync** *(Result&lt;Task&lt;T&gt;&gt; result)*  

<a id="Monacs.Core.Async.Result.TryCatchAsync(,System.Func`2[[System.Exception, mscorlib, Version=4.0.0.0, Culture=neutral, PublicKeyToken=b77a5c561934e089],[Monacs.Core.ErrorDetails, Monacs.Core, Version=1.0.0.0, Culture=neutral, PublicKeyToken=null]])"></a>

* *Task&lt;Result&lt;T&gt;&gt;* **TryCatchAsync** *(Func&lt;Task&lt;T&gt;&gt; func, Func&lt;Exception, ErrorDetails&gt; errorHandler)*  

<a id="Monacs.Core.Async.Result.TryCatchAsync(,,)"></a>

* *Task&lt;Result&lt;TOut&gt;&gt;* **TryCatchAsync** *(Result&lt;TIn&gt; result, Func&lt;TIn, Task&lt;TOut&gt;&gt; func, Func&lt;TIn, Exception, ErrorDetails&gt; errorHandler)*  




---

