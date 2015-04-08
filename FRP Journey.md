## Journey to better understanding FRP
( by [@ninokierulf](https://github.com/ninokierulf) )  
created: 2015 April 02  
modified: 

## Learnings

* FP is not same as FRP
* concepts of pure and unpure, first class, higher order

### After reading [Collection Pipeline Patterns](http://martinfowler.com/articles/collection-pipeline/) by Martin Fowler.  
* `map` - to transform item (similar to select?)
* `flatten` - merge nested
* `flat-map` - map with flatten 1 level
* `reduce` - similar to an accumulator? results in one return object
* `intersection` - results in common objects in both universe


ReactiveCocoa(RAC) notable differences include:

 * `-map:` instead of `Select`
 * `-filter:` instead of `Where`
 * `-flatten` instead of `Merge`
 * `-flattenMap:` instead of `SelectMany`


## Bookmarks  
* [Rx Links and Tutorials](http://reactivex.io/tutorials.html)
* [Collection Operation Catalog](http://martinfowler.com/articles/collection-pipeline/#op-catalog)
* [Visualizing Rx Operators 1](http://staltz.com/rxmarbles/)
* [Visualizing Rx Operators 2](http://calavoow.github.io/reactivex.github.io/operators/)
* [Rx io](http://reactivex.io/)
* [reactivemanifesto](http://www.reactivemanifesto.org/)
* [ReactiveX on Github](https://github.com/ReactiveX)
* [ReactNative by Facebook](http://facebook.github.io/react-native/)
* **[RxSwift](https://github.com/jspahrsummers/RxSwift)**
* [ReactiveSwift](https://github.com/hisui/ReactiveSwift)
* [ReactKit](https://github.com/ReactKit/ReactKit)


### People to follow

1. Martin Fowler
	* [Personal Website](http://martinfowler.com/)
	* [Collection Pipeline](http://martinfowler.com/articles/collection-pipeline)
	
	 
2. Andre Medeiros (aka Staltz)
	* [Personal Website](http://andre.staltz.com/)
	* [Medium](https://medium.com/@andrestaltz)
	* [Intro to Rx](https://gist.github.com/staltz/868e7e9bc2a7b8c1f754)
	* [Rx example via jsfiddle](http://jsfiddle.net/staltz/8jFJH/48/)
	
3. Conal Elliott  
	* [Push-Pull FRP](http://conal.net/papers/push-pull-frp/)
	* [Simply Reactive](http://conal.net/papers/simply-reactive/) [unread]
	* [Lambda the Ultimate](http://lambda-the-ultimate.org/node/2756) [unread]
	

### Articles Read (Chronological)
[Reactive Swift](https://medium.com/swift-programming/reactive-swift-3b6050375534)  
[Intro to Rx](https://gist.github.com/staltz/868e7e9bc2a7b8c1f754)  by Staltz  
[Collection Pipeline](http://martinfowler.com/articles/collection-pipeline) by Martin Fowler  
[Be Reactive](http://colintheshots.com/blog/?p=85) by colintheshots  
[stackoverflow answer](http://stackoverflow.com/questions/1028250/what-is-functional-reactive-programming/1028642#1028642) by Laurence Gonsalves  
[Push Pull FRP](http://conal.net/papers/push-pull-frp/) by Conal Elliott  
[FP in Swift](http://floriankugler.com/2014/10/03/functional-programming-in-swift/) by Florian Kugler  
[FP Swift Realm.io](https://realm.io/news/functional-programming-swift-chris-eidhof/) by Chris Eidhof  
[FP should be your priority](https://medium.com/@jugoncalves/functional-programming-should-be-your-1-priority-for-2015-47dd4641d6b9) by Ju Gonçalves  
[FRP by Haskell.org](https://wiki.haskell.org/Functional_Reactive_Programming)  
[Reactive Programming](http://blog.reactiveprogramming.org/) by Stephen Blackheath  
[FRP Reflections](https://lukepalmer.wordpress.com/2009/12/20/reflections-on-a-holy-grail-frp/) - funny/witty

### To Read
* [Hot and Cold Observables](http://leecampbell.blogspot.co.uk/2010/08/rx-part-7-hot-and-cold-observables.html)  
* [The Last Language?](http://lambda-the-ultimate.org/node/4312)
* http://lambda-the-ultimate.org/node/2756
* http://conal.net/fran/tutorial.htm
* [Swift FRP](https://speakerdeck.com/ashfurrow/functional-reactive-programming-in-swift) by Ash Furrow
* [SwiftBond](https://github.com/SwiftBond/Bond)
* [potatotips](https://github.com/potatotips/potatotips/wiki)
* http://www.objc.io/issue-16/functional-swift-apis.html
* [FRP in Swift](https://speakerdeck.com/chriseidhof/functional-programming-in-swift) by Chris Eidhof
* [Enemy of the State](https://speakerdeck.com/jspahrsummers/enemy-of-the-state) by @jspahrsummers
* [LearnYouAHaskell](http://learnyouahaskell.com/chapters)
* [Rx 101](http://rxwiki.wikidot.com/101samples)
* [RAC](http://www.slideshare.net/Cegeka/reactive-cocoa-v2-copy) presentation by Cegeka
* [Swift FR](http://www.slideshare.net/alexis_gallagher/swift-functional-programming-and-the-future-of-obj-c) presentation by alexis_gallagher

## Libraries
* [Functional ViewControllers](https://github.com/chriseidhof/functional-view-controllers) by Chris Eidhof
	: Here's an [article](http://chris.eidhof.nl/posts/functional-view-controllers.html) about it

