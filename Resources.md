
[Software](06357742-dd87-4fb1-8b88-f06c5c5477a5)


	[Programming languages](aa8ea4e8-377a-4140-a0fb-6b63b46906fb)


		[Reason](d90533ec-ad6d-475e-87c0-29d0c6365639)


			Quick Guide [https://github.com/amartincolby/ReasonML-Quick-Guide](https://github.com/amartincolby/ReasonML-Quick-Guide)


			### Workshop material


			[https://github.com/fakenickels/rancho-dev-reasonml-es2077](https://github.com/fakenickels/rancho-dev-reasonml-es2077)


			[https://protoship.io/blog/materials-for-learning-reasonml/](https://protoship.io/blog/materials-for-learning-reasonml/)


			[https://github.com/nikgraf/2019-10-reason-workshop](https://github.com/nikgraf/2019-10-reason-workshop)
			[https://github.com/fakenickels/es2077-reactconf](https://github.com/fakenickels/es2077-reactconf)


			[https://github.com/arecvlohe/reasonml-cheat-sheet](https://github.com/arecvlohe/reasonml-cheat-sheet)


			### Language discussions


			[https://blog.dubenko.dev/typescript-vs-reason/](https://blog.dubenko.dev/typescript-vs-reason/)
			[https://gist.github.com/busypeoples/270f29ec6cdd45780889c53e7b52884a](https://gist.github.com/busypeoples/270f29ec6cdd45780889c53e7b52884a)


			[https://stackoverflow.com/questions/46147250/reasonml-vs-typescript/46935302#46935302](https://stackoverflow.com/questions/46147250/reasonml-vs-typescript/46935302#46935302)


			[https://stackoverflow.com/questions/51015850/reasonml-vs-elm/51027309#51027309](https://stackoverflow.com/questions/51015850/reasonml-vs-elm/51027309#51027309)


			[https://twitter.com/codeptualize/status/1167876567487303681](https://twitter.com/codeptualize/status/1167876567487303681)


			[https://formidable.com/blog/2021/reason-2021/](https://formidable.com/blog/2021/reason-2021/)


			### ReasonML Advanced

			- [https://stackoverflow.com/questions/55474593/whats-the-difference-between-and-in-reasonml](https://stackoverflow.com/questions/55474593/whats-the-difference-between-and-in-reasonml)
			- Making Impossible States Impossible in ReasonML [https://gist.github.com/busypeoples/ab2f993843f23614232a1f8500a4b542](https://gist.github.com/busypeoples/ab2f993843f23614232a1f8500a4b542)
			- [https://github.com/ostera/reason-design-patterns](https://github.com/ostera/reason-design-patterns)
			- [https://dev.to/mlms13/type-classes-in-reasonml-a-world-of-functions-for-free-2lag](https://dev.to/mlms13/type-classes-in-reasonml-a-world-of-functions-for-free-2lag)
			- [https://andywhite.xyz/posts/2019-11-01-a-laymans-guide-to-functors-in-reasonml/](https://andywhite.xyz/posts/2019-11-01-a-laymans-guide-to-functors-in-reasonml/)

			### Why Reason


			[https://medium.com/@johnhaley81/why-reasonml-part-1-8a975bbcf5f7](https://medium.com/@johnhaley81/why-reasonml-part-1-8a975bbcf5f7)


			[https://blog.logrocket.com/what-makes-reasonml-so-great-c2c2fc215ccb/](https://blog.logrocket.com/what-makes-reasonml-so-great-c2c2fc215ccb/)
			[https://www.freecodecamp.org/news/psst-heres-why-reasonreact-is-the-best-way-to-write-react-5088d434d035/](https://www.freecodecamp.org/news/psst-heres-why-reasonreact-is-the-best-way-to-write-react-5088d434d035/)


			[Things about Reason/OCaml that I don't know](8f2995f0-8aac-4a37-a545-be285ab47f67)


				<details>
				  <summary>"%identity"</summary>
				
				- external string: string => element = "%identity";
				- "%identity" is special Bucklescript instruction that does nothing but convert from the type string to element in this case.
				- is a way to coerce one type to another without runtime checks, it's therefore unsafe and actually shouldn't be used too much: [https://reasonml.org/docs/reason-compiler/latest/intro-to-external#special-identity-external](https://reasonml.org/docs/reason-compiler/latest/intro-to-external#special-identity-external)
				- [https://bucklescript.github.io/docs/en/intro-to-external#special-identity-external](https://bucklescript.github.io/docs/en/intro-to-external#special-identity-external)
				
				
				  </details>


				<details>
				  <summary>Relation with BuckleScript buildin types and Reason types</summary>
				
				- `Js.Array2.t` vs `Js.Array.t` vs  `array` (Reason/OCaml).
				- `bs.obj` vs `Js.t({...})` vs `{. "": ""}` vs `{.. "": ""}`
					- [https://reasonml.github.io/try?rrjsx=true&reason=C4TwDgpgBA9gRgKwIIGcBSKAqUC8UDeAdFAEQB2AhgLYQkBcUKwATgJZkDmUAvgNwBQoSLESoMwXFAyFgACnz8oUQoqiUaDJm079uASgGDw0eAggBjYAEkyAeXPUANpKJrqETS3Zc+R4TEgyCAATW0QLCVkAcgo9F0JidQ9GL04eKAoUKBiBIA](https://reasonml.github.io/try?rrjsx=true&reason=C4TwDgpgBA9gRgKwIIGcBSKAqUC8UDeAdFAEQB2AhgLYQkBcUKwATgJZkDmUAvgNwBQoSLESoMwXFAyFgACnz8oUQoqiUaDJm079uASgGDw0eAggBjYAEkyAeXPUANpKJrqETS3Zc+R4TEgyCAATW0QLCVkAcgo9F0JidQ9GL04eKAoUKBiBIA)
				
				
				  </details>


				<details>
				  <summary>BuckleScript decorators. </summary>
				
				
				
				  </details>


				<details>
				  <summary>Reason bindings: </summary>
				
				
				
				  </details>


				<details>
				  <summary>try/catch + exceptions?</summary>
				
				- 👍
				
				
				  </details>


				<details>
				  <summary>open!</summary>
				
				
				Both make the values and types in `My_module` available without having to write “My_module.” in front of them. `open My_module` will trigger a warning if `My_module` overrides existing definitions. `open!` suppresses this warning. See [Overriding in open statements](http://caml.inria.fr/pub/docs/manual-ocaml/extn.html#sec250) from [Chapter 8 Language extensions](http://caml.inria.fr/pub/docs/manual-ocaml/extn.html) in the OCaml manual.
				At present `open!` also suppresses another warning as well. This is a warning that no definition in the opened module is in fact used within `open!`’s scope. There is some disagreement about whether this behavior is desirable. Those who use `open!` for this purpose use it to open modules such as `Core`, `Batteries`, or `Containers` that shadow many built-in definitions, using such a module as a way of providing an alternative standard programming environment. See the discussion at this OCaml PR: [Fix PR6638: “unused open” warning was incorrectly suppressed by “open!”](https://github.com/ocaml/ocaml/pull/1110).
				
				
				
				  </details>


				<details>
				  <summary>open polyvars: [> | `Lola | `Flores]</summary>
				
				
				
				  </details>


				<details>
				  <summary>generic types</summary>
				
				
				
				  </details>


				<details>
				  <summary>Phanton types</summary>
				
				
				[https://gist.github.com/busypeoples/3a28d039272ec3eb33ca2fc6b32dafc7](https://gist.github.com/busypeoples/3a28d039272ec3eb33ca2fc6b32dafc7)
				
				
				
				  </details>


				<details>
				  <summary>first-class modules</summary>
				
				- [https://medium.com/@Pooch/functors-first-class-modules-in-reason-b4bb1461d849#cee0](https://medium.com/@Pooch/functors-first-class-modules-in-reason-b4bb1461d849#cee0)
				
				
				  </details>


				<details>
				  <summary>type </summary>
				
				
				[https://dev.to/mlms13/type-classes-in-reasonml-a-world-of-functions-for-free-2lag](https://dev.to/mlms13/type-classes-in-reasonml-a-world-of-functions-for-free-2lag)
				
				
				
				  </details>


				<details>
				  <summary>let module</summary>
				
				
				
				  </details>


				<details>
				  <summary>Error message: a type is not compatible with itself ?</summary>
				
				
				[http://caml.inria.fr/pub/old_caml_site/FAQ/FAQ_EXPERT-eng.html#message_incomprehensible](http://caml.inria.fr/pub/old_caml_site/FAQ/FAQ_EXPERT-eng.html#message_incomprehensible)
				
				
				
				  </details>


				<details>
				  <summary>Stuff about ppx</summary>
				
				- ocaml-migrate-parsetree [https://reasonml.chat/t/ppx-no-need-for-separate-ppx-and-ppx6-with-ocaml-migrate-parsetree-1-6-0/2210](https://reasonml.chat/t/ppx-no-need-for-separate-ppx-and-ppx6-with-ocaml-migrate-parsetree-1-6-0/2210)
				- [https://discuss.ocaml.org/t/the-future-of-ppx/3766/18](https://discuss.ocaml.org/t/the-future-of-ppx/3766/18)
				
				
				  </details>


				### OCaml


				<details>
				  <summary>ocamlopt</summary>
				
				
				
				  </details>


				<details>
				  <summary>opam</summary>
				
				
				[opam](9dcb06e2-12ce-4ca2-88fa-40bd9ce2eaa2)
				
				
					[https://khady.info/opam-npm.html](https://khady.info/opam-npm.html)
				
				
					[https://khady.info/opam-sandbox.html](https://khady.info/opam-sandbox.html)
				
				
					[https://khady.info/opam-compilation-cache.html](https://khady.info/opam-compilation-cache.html)
				
				
					[https://khady.info/2018-04-15-setup-reasoncli-opam.html](https://khady.info/2018-04-15-setup-reasoncli-opam.html)
				
				
				
				  </details>


				<details>
				  <summary>Understanding dune</summary>
				
				
				
				  </details>


				<details>
				  <summary>[@@deriving]</summary>
				
				- [https://medium.com/cryptosense-tech/how-to-get-the-best-out-of-ppx-deriving-fcb29c76dcc0](https://medium.com/cryptosense-tech/how-to-get-the-best-out-of-ppx-deriving-fcb29c76dcc0)
				
				
				  </details>


				<details>
				  <summary>ocamlfind</summary>
				
				
				
				  </details>


				<details>
				  <summary>'a.</summary>
				
				
				
				  </details>


				### esy

				- `esy b test` vs `esy test`. I do understand that `esy b` is an alias to `esy build`, but when you run something with `esy build test` does it run inside the _build folder? What's the difference?

		[OCaml](eb918152-b2eb-46b5-8e9e-9741cf5f852e)


			[Learning](535e94ec-477f-48d8-8bb5-c3037c8215f6)


				Live learn OCaml exercises [https://ocaml-sf.org/learn-ocaml-public/#activity%3Dexercises](https://ocaml-sf.org/learn-ocaml-public/#activity%3Dexercises) Repo [https://github.com/ocaml-sf/learn-ocaml-corpus](https://github.com/ocaml-sf/learn-ocaml-corpus)


				Introduction to Functional Programming in OCaml [https://www.fun-mooc.fr/courses/course-v1:parisdiderot+56002+session04/about](https://www.fun-mooc.fr/courses/course-v1:parisdiderot+56002+session04/about)


				[https://ocaml.org/releases/4.12/htmlman/coreexamples.html](https://ocaml.org/releases/4.12/htmlman/coreexamples.html)


				UNIX SYSTEM PROGRAMMING IN OCAML [https://ocaml.github.io/ocamlunix/ocamlunix.pdf](https://ocaml.github.io/ocamlunix/ocamlunix.pdf)


				Using, Understanding, and Unraveling The OCaml Language [https://caml.inria.fr/pub/docs/u3-ocaml/ocaml.pdf](https://caml.inria.fr/pub/docs/u3-ocaml/ocaml.pdf)


				OCaml Programming: Correct + Efficient + Beautiful 
				CS 3110 at Cornell University [https://github.com/cs3110/textbook](https://github.com/cs3110/textbook)


				**What I wish I knew when learning OCaml** [https://baturin.org/docs/ocaml-faq/](https://baturin.org/docs/ocaml-faq/)


			[Best practices](29f1c2c7-acb8-4190-80b4-209d15569bbf)


				by issuu


				[https://engineering.issuu.com/2018/11/20/our-current-ocaml-best-practices-part-1](https://engineering.issuu.com/2018/11/20/our-current-ocaml-best-practices-part-1)


				[https://engineering.issuu.com/2018/12/10/our-current-ocaml-best-practices-part-2](https://engineering.issuu.com/2018/12/10/our-current-ocaml-best-practices-part-2)


			[Compiler](95b6159f-b980-46d0-85b4-6c3467c7a63a)


				OCaml comprises two compilers. One generates bytecode which is then interpreted by a C program. This compiler runs quickly, generates compact code with moderate memory requirements, and is portable to essentially any 32 or 64 bit Unix platform. Performance of generated programs is quite good for a bytecoded implementation. This compiler can be used either as a standalone, batch-oriented compiler that produces standalone programs, or as an interactive, toplevel-based system.


				The other compiler generates high-performance native code for a number of processors. Compilation takes longer and generates bigger code, but the generated programs deliver excellent performance, while retaining the moderate memory requirements of the bytecode compiler.


				The OCaml Compiler [https://sookocheff.com/post/ocaml/the-ocaml-compiler-pipeline](https://sookocheff.com/post/ocaml/the-ocaml-compiler-pipeline/)


			[Functors](b74f2fb9-4622-4504-9ada-28ed62019dfd)

				- [https://www.thekerneltrip.com/ocaml/ocaml-functor-example](https://www.thekerneltrip.com/ocaml/ocaml-functor-example/)
				- [https://dev.realworldocaml.org/functors.html](https://dev.realworldocaml.org/functors.html)

			[Lenses](ad902921-d3c3-4786-a7a2-7824c98b429e)

				- [https://jobjo.github.io//2017/12/20/lenses-as-modules.html](https://jobjo.github.io//2017/12/20/lenses-as-modules.html)

			[Lwt](60107c87-e693-4b30-8cb0-6ab428cc0cef)


				[https://ocsigen.org/lwt/5.2.0/manual/manual](https://ocsigen.org/lwt/5.2.0/manual/manual)


				[https://jobjo.github.io/2020/07/01/beyond-lwt-promises.html](https://jobjo.github.io/2020/07/01/beyond-lwt-promises.html)


			[atd](c1e57ad1-c3b7-4e2f-982c-e322fdab07ef)


				[https://github.com/ahrefs/atd](https://github.com/ahrefs/atd)


				[https://github.com/feihong/atdgen-workshop](https://github.com/feihong/atdgen-workshop)


				[https://atd.readthedocs.io/en/latest/tutorial.html#integration-with-build-systems](https://atd.readthedocs.io/en/latest/tutorial.html#integration-with-build-systems)


				[https://tech.ahrefs.com/getting-started-with-atdgen-and-bucklescript-1f3a14004081](https://tech.ahrefs.com/getting-started-with-atdgen-and-bucklescript-1f3a14004081)


			🤓 Reader monad [https://jobjo.github.io//2020/09/20/type-safe-dependencies.html](https://jobjo.github.io//2020/09/20/type-safe-dependencies.html)


			📦 opam [https://khady.info/opam-npm.html](https://khady.info/opam-npm.html)


			Testing: [https://dev.realworldocaml.org/testing.html](https://dev.realworldocaml.org/testing.html)


			API Client


			[https://github.com/nv-vn/TelegraML](https://github.com/nv-vn/TelegraML)


			[https://github.com/digitake/bs-rest-api](https://github.com/digitake/bs-rest-api)


			cmdliner [https://github.com/mjambon/cmdliner-cheatsheet](https://github.com/mjambon/cmdliner-cheatsheet)


			[https://medium.com/@bobbypriambodo/interfacing-ocaml-and-postgresql-with-caqti-a92515bdaa11](https://medium.com/@bobbypriambodo/interfacing-ocaml-and-postgresql-with-caqti-a92515bdaa11)


			re2 


			Textbook CS 3110 [https://cs3110.github.io/textbook](https://cs3110.github.io/textbook/)


			OCaml for the Masses [https://queue.acm.org/detail.cfm?id=2038036](https://queue.acm.org/detail.cfm?id=2038036)


			[Forum posts that are gold](2520e60a-9039-4943-9c10-d978abe90c8e)


				[https://discuss.ocaml.org/t/why-should-i-use-ocaml/7064/4](https://discuss.ocaml.org/t/why-should-i-use-ocaml/7064/4)


				### Documentation


				[https://discuss.ocaml.org/t/ocaml-documentation-open-thread/1841](https://discuss.ocaml.org/t/ocaml-documentation-open-thread/1841)


				[https://discuss.ocaml.org/t/suggestions-for-ocaml-documentation/4504/22](https://discuss.ocaml.org/t/suggestions-for-ocaml-documentation/4504/22)


				?? [https://discuss.ocaml.org/t/ocaml-first-impressions/517](https://discuss.ocaml.org/t/ocaml-first-impressions/517)


				[https://www.reddit.com/r/ocaml/comments/tkqgqu/bad_documentation_of_jane_street_libraries/?utm_source=share&utm_medium=ios_app&utm_name=iossmf](https://www.reddit.com/r/ocaml/comments/tkqgqu/bad_documentation_of_jane_street_libraries/?utm_source=share&utm_medium=ios_app&utm_name=iossmf)


			[ReScript history](00a08acb-1ffc-45cf-b6f0-ab74e808d0ea)


				[https://news.ycombinator.com/item?id=10860815](https://news.ycombinator.com/item?id=10860815)


				[https://github.com/little-arhat/ocaml-fb-react-playground](https://github.com/little-arhat/ocaml-fb-react-playground)


				[https://gist.github.com/jordwalke/67819c91df1552009b22](https://gist.github.com/jordwalke/67819c91df1552009b22)


		[JavaScript](c44bdbd2-f8d0-4726-a1c5-f3b533ff0e30)


			[Articles](65187f5a-9514-49df-8823-cb8b5be49303)


				[JavaScript Code Smells](http://elijahmanor.com/talks/js-smells/#/8/2)


				[Understanding MVC And MVP (For JavaScript And Backbone Developers)](http://addyosmani.com/blog/understanding-mvc-and-mvp-for-javascript-and-backbone-developers/)


				[Master the JavaScript Interview: What’s the Difference Between Class & Prototypal Inheritance? — JavaScript Scene — Medium](https://medium.com/javascript-scene/master-the-javascript-interview-what-s-the-difference-between-class-prototypal-inheritance-e4cd0a7562e9#.fkeazipgq)


				[Learning JavaScript Design Patterns](http://addyosmani.com/resources/essentialjsdesignpatterns/book/#revealingmodulepatternjavascript)


				[Named function expressions demystified](http://kangax.github.io/nfe/)


				[JavaScript Fundamentals](http://www.datchley.name/tag/fundamentals/)


				[JavaScript Objects: Inherited a Mess](http://davidwalsh.name/javascript-objects)


				[JavaScript Closures](http://jibbering.com/faq/notes/closures/#clIRExSc)


				[ES6 Promises in Depth](https://ponyfoo.com/articles/es6-promises-in-depth)


				[What Is This Thing Called Generators?](http://tobyho.com/2013/06/16/what-are-generators/)


				[Exploring Async JS](https://github.com/thalesmello/exploring-async/blob/master/exploring_async.md)


				[How do JavaScript closures work under the hood [Dmitry Frank]](http://dmitryfrank.com/articles/js_closures)


				[Introduction to Communicating Sequential Processes in JavaScript](http://dialelo.github.io/introduction-to-communicating-sequential-processes-in-javascript.html)


				[all this](http://bjorn.tipling.com/all-this)


				[JavaScript Promises ... In Wicked Detail - Matt Greer](http://www.mattgreer.org/articles/promises-in-wicked-detail/)


				[JavaScript Concepts OLD FAQ](http://jibbering.com/faq/)


				[JavaScript Playground](http://javascriptplayground.com/)


				[JavaScript DDD](http://gcanti.github.io/tcomb/)


				[Front-end Code Standards & Best Practices | Isobar](http://isobar-idev.github.io/code-standards/)


				[Pocket-sized JavaScript - The dot Post](http://www.thedotpost.com/2015/12/henrik-joreteg-pocket-sized-javascript)


			[Books](0c99ab7c-0145-4dee-8c72-0cae9826a86b)


				[BOOK Mostly Adequate Guide](http://drboolean.gitbooks.io/mostly-adequate-guide/content/)


				[javascript-society/javascript-path](https://github.com/javascript-society/javascript-path)


				[10 Free JavaScript Books](http://sixrevisions.com/javascript/free-javascript-books/)


				[Javascript Challenges](https://www.gitbook.com/book/amischol/javascript_challenges/details)


				[You-Dont-Know-JS/README.md at master · getify/You-Dont-Know-JS](https://github.com/getify/You-Dont-Know-JS/blob/master/es6%20&%20beyond/README.md#you-dont-know-js-es6--beyond)


			[ES6 Interactive Guide](http://projects.formidablelabs.com/es6-interactive-guide/#/)


			[ECMAscript 6 Lessons - Screencast Video Tutorials @eggheadio](https://egghead.io/technologies/es6)


			[Learn ES2015 · Babel](https://babeljs.io/docs/learn-es2015/)


			[Exploring ES6](http://exploringjs.com/es6/)


			[Asynchronous calls with ES6 generators – Minko Gechev's blog](http://blog.mgechev.com/2014/12/21/handling-asynchronous-calls-with-es6-javascript-generators/)


			[React](35fa6387-f6bc-4737-9738-6b4a950412cf)


				[link_preview](https://github.com/jordwalke/FaxJs)


			**How JavaScript Works behind the scenes?** [https://blog.devgenius.io/how-javascript-works-behind-the-scenes-88c546173f32](https://blog.devgenius.io/how-javascript-works-behind-the-scenes-88c546173f32)


			**Inside the JavaScript Engine** [https://blog.devgenius.io/inside-the-javascript-engine-bb7b9f26e84b](https://blog.devgenius.io/inside-the-javascript-engine-bb7b9f26e84b)


		[Typescript](c893b740-d6f3-4bc4-8535-02861d16f529)


			[https://www.freecodecamp.org/news/typescript-curry-ramda-types-f747e99744ab/](https://www.freecodecamp.org/news/typescript-curry-ramda-types-f747e99744ab/)


			[Why TypeScript](e78b6252-0d15-4541-b786-2ae246b2628d)


				The reliability of your code. It makes illegal states unrepresentable.
				Implement the business rules in your code : the IDE will warn you if you do not stick to them.


				---


				The only real selling point is hype and adoption. People use it, therefore there's demand for people who know it and libs that use it.
				
				From a practical perspective, I don't think TS is production ready **yet**. Maybe someday.


				---


				gradual adoption. like, you can start in one file, or for just new code, and can incrementally add it to your codebase (and similarly, you can back out of it easily)


				---


				Dev experience in maintaining the code


				---


				Intellisense and everything that comes with that. No more looking through docs to find fn signatures. Easily change your own functions and know every place you broke. Move stuff around effortlessly. Allows you to stop storing the entire codebase in your head.


				---


				IDE autocomplete, and surfacing API signatures while developing.
				
				It’s best when used minimally & the inference engine does as much as possible. The more custom types there are I find the code is *worse* to maintain & takes longer to develop in.
				
				But it’s useful.


				Note: custom types, not type signatures.
				
				Typing itself is fine, but having to recreate complex custom types just to do something that *will* work but TS isn’t happy about (because the devs over complicated the type) has wasted more time that TS has saved.
				
				Project depending ofc


				---


				I like the intellisense much better, very helpful for getting around a code base. The code becomes self documening if types are done well and easy to maintain. If types are not thought through you end up with lots of optional params and any type which feels like boilerplate on JS


				---


				At my last company it was that standard CS grads could understand TS easier than vanilla JS since most schools focus heavily on OOP. We wanted JS to be a shared language for frontend & backend, went TS to be able to hire talent into both a little easier.


				---


				Knowing what you’re going to break before breaking it. I find it super useful for API changes across components, autocompletion and even documentation. The bad point al least for me is the learning curve.


				---


				That it makes people who come from statically typed language understand better. creating a bunch of any types or just an random object of data for example confused the hell out of me. Like ok  i guess we can do that in js


				---


				It’s just another abstraction layer. You can encode compile-time logic in static types and write less runtime code.
				
				Also I spent ten years writing JS and then having to run it and see if it actually worked or not. TS lets you know by looking at it.


				---


				I love the self-documentation nature of it. Being able to right-click into a type definition and seeing everything can help provide clarity and direction.


				---


				Well, for the folks like me who has a classical CS background and has primarily worked with typed languages, it's the convenience of having types which in addition makes code much more robust.


				---


				autocomplete, type check, etc as people are bored to write boiler plate code which will in-turn give more time to focus on business logic than wasting time to find out from where method is "undefined" error is originating from


				---


				It's the ability to create generics, interfaces, records, enums, abstract classes, etc... along with many other advanced types that make code more extensible and concise.
				
				Additionally the optional static typing enables an amazing intellisense experience.


				---


				apart from all the type safety, i love it when we have a nodejs backend.
				i share the interfaces and types between backend, ui and background services.
				Integration between services is a breeze.


				---


				There are so many … conceptual and practical ones ! If I had to pick one and be practical, maintaining your code and knowing exactly what a function expects feel so comfortable and robust. Going back to vanilla after coding in TS really makes one realize all TS brings


				---


				Opt in type safety. So easy to get started and once you do, it becomes to good to live without because of auto complete.


				---


				check your docs. 
				
				Some long time ago.. We use JS libraries with wrong docs (website or just out of date JSDoc), so Typescript bring us the real THRUTH !!!
				
				 For example, today you can to this:
				
				`tsc --noEmit --allowJS --checkJS`
				
				and verify if your js code match your jsdoc !!!


				---


				For me, the selling point was the ability to refactor code without fear to break something. Because of types, of course:)


				---


				My favourite part though is progressive opt in. You can still write “unsafe” code. It will run. Which is really nice for prototyping.


				---


				Also, structural types is way better for something like the web platform  where you might be getting resources from 10^43 apis and working with 2^45432 npm packages. 
				
				Structural > Nominative for the web.


				---


				JS is too fragile. TS makes it less unpredictable.
				
				It's not true for all dynamic languages though.


				---


				JS classes + propTypes are good enough for me, but I primarily work on small projects where I am the lead. If I was working on a big project working across teams I’d want TS. You don’t need courts if you’re the only one in the village.


				---


				Handling errors that might not occur on js AND autocompletion - definetly the autocompletion stuff


				---


				Not having to remember what function parameters are and what types they expect


				---


				It self documents better, which often makes the code more maintainable. and the TypeScript language server means that the intellisence, provides the groundwork was laid, is hard to beat.


				---


				That feeling you have when you try to go back to javascript, after using TS for a few months. That uncertainty when you call a function written in JS, and there is no type checking, and you have to go and read your implementation to figure out if the first param should be.


				---


				Type safety!
				
				And with intellisence you don't need to do as much error handling in development. 
				Errors that otherwise would only be found at runtime can be mitigated if you use a static typed language
				
				"building complex stuff" with js require much more work than doing it with ts


				---


				Compile check at build time not runtime. I want to catch mistakes before I run the code not after. I have been building a large internal app and typescript has caught so many of my own errors and I am never worried when I push a commit. It works 99.99% of the time.


				---


				It’s metadata about your code that you can refer to or additional information. It’s documentation that self enforces that your following it.


				---


				Depends who you sell it to. No vendor lock in might be important for some. You can always transpile to esnext and are back at JS.


				---


				Forced documentation with the side effect of making your code run more safely


				---


				Feeling safer while writing JavaScript (good typings required), code autocompletion works really nice, documentation in the editor, etc.


				---


				You get some of the nice things you would get from statically, strongly typed languages like Haskell, but you don't need to rewrite your entire codebase and you can slowly move away from JS


				The main benefit I see is fearless refactoring: with types if you get something wrong (and don't abuse `any`), the compiler / transpiler will yell at you! This makes it easier to refactor huge portions of code without too much worry


				---


				Gives me all the benefits of JSDoc Annotations without writing JSDoc Annotations in VSCode. I get type annotations in my code, and some idea of what something is or isn't supposed to be (especially in a larger codebase with many modules), without being reliant on reading code.


				---


				Less runtime errors/bugs in production and more compile-time errors instead!


				---


				"make your codebase typesafe"*
				
				Terms & conditions apply 
				*(by replacing variable types with a bunch of OR list of types everywhere and by adding a pre processor to make compile down to js anyway just paying with complexity of pipeline and code itself)


				---


				Compile time safety. Change a function signature? error. Change a type? Error. Spell a var name wrong? Error. All of this without having to hit the browser.


				---


				More accessible than test-driven development but with some of the benefits, i.e., fearless refactoring, etc.


				---


				My favorite thing about [@typescript](https://twitter.com/typescript) is how easy it is to refactor my code. The types empower my tools to do extraordinary things that make my job easier.


				---


				Refactors


				---


				- Extremely gradual/incremental type system.
				- Clever top & bottom type design
				- Compile to JS
				- Projects like Prisma, io-ts
				- Low diffusion
				- Ever becoming better type inference
				- Unique stuff like template strings, interpolates types, etc.
				- And yes, structural typing


				---


				I’m blown away by the amount of typescript hate  Type safety is number one (if you don't abuse "any"), but browser compatibility is probably #2! Transpile fancy new JavaScript to old stuff that works on all browsers.


				---


				It is in the name (they chose a good one) - JavaScript but with Types.


				---


				Interfaces and compile time safety (a lot of people hate it and think it's overbearing but they never stop to configure it)


				---


				Think Error showing in runtime and absolutely JavaScript is the selling point


				---


				typing is optional, so if you need, you can always go dirty and thats huge.


				---


				It's made by the same company that made Internet Explorer lol.


				---


				you realise how great defining static types is after spending a day solving that bug in your javascript react app


				---


				A clear linking path in the flow of your application. You can see what is referencing what which makes problem diagnosis much simpler.


				---


				code maintenance and finally some intellisense for frontend


				---


				Fearless refactoring. Change the shape of a core data structure, fix the 1000s of errors, and when you’re done, be confident you’re not shipping a bug.


				---


				Being yelled at for making mistakes, I undermined how hard debugging can get. It's awesome to see those red underlines, fix them and be almost certain that things will now work.


				---


				type safety


				---


				Trustworthy intellisense
				
				Being able to know what any variable or object contains is the best productivity tool ever.
				
				Especially when you touch code after 6 months where you how the data looked like


				---


				Sorry models is the answer (which types comprise). Coding without models is like going to work in a diaper.


				---


				Everybody else is doing it so I guess I'll do it too.


				---


				compile linting errors in dev pipeline => less bugs in production


				---


				As maintainability is mentioned various times already, I'll go for its predictability.


				---


				- Makes code more readable, there is a reason why almost everyone that adopts it sticks with it.
				- Easier to debug
				- Saves a lot of the InputOutput testing
				- Catches bugs during developement, if you declare something that is empty/null, your IDE will scream at you to fix it.


				---


				Leveraging the JS ecosystem without suffering so much


				---


				Documentation it creates around the codebase is the best thing I like about TS


				---


			[Runtime static validation libs](f6059c7d-af95-4df9-ad97-99a3cf5cc72d)


				[bookmark](https://github.com/colinhacks/zod)


				[bookmark](https://github.com/gcanti/io-ts)


				[bookmark](https://github.com/nvie/decoders)


				[bookmark](https://github.com/sideway/joi)


			[https://www.npmjs.com/package/promises-fn-utils](https://www.npmjs.com/package/promises-fn-utils)


			Dependant types [https://twitter.com/benmvp/status/1473823066333454336](https://twitter.com/benmvp/status/1473823066333454336)


			Blind spots [https://incrementalelm.com/typescript-blind-spots/](https://incrementalelm.com/typescript-blind-spots/)


			**Introduction to Functional Programming using TypeScript and fp-ts.** [https://github.com/enricopolanski/functional-programming](https://github.com/enricopolanski/functional-programming)


			**Generics in useLoader** [https://github.com/remix-run/remix/pull/1254](https://github.com/remix-run/remix/pull/1254)


			[Type challenge](883c24e1-cdd1-4b7d-850e-976b6cc82e7e)


				`A extends B` → `A` is assignable to `B`. “Returns” boolean


				`…A` → deconstruct A


				`infer A`


				---


			**Reconstructing TypeScript** [https://jaked.org/blog/2021-09-07-Reconstructing-TypeScript-part-0](https://jaked.org/blog/2021-09-07-Reconstructing-TypeScript-part-0)


			**Deep dive** [https://basarat.gitbook.io/typescript/main-1/nominaltyping](https://basarat.gitbook.io/typescript/main-1/nominaltyping)


		[Rust](4c9c6f48-d966-426e-b7e1-fcb73e8cdeee)


			[https://github.com/jondot/rust-how-do-i-start](https://github.com/jondot/rust-how-do-i-start)


			[http://rustforjs.dev](http://rustforjs.dev/)


		[Elm](cd3348c6-6fb5-40b9-85fa-c83e87446a89)


			[https://blog.joelabshier.com/converting-react-app-to-elm-app](https://blog.joelabshier.com/converting-react-app-to-elm-app/)


		**Great mini ideas from all PLs** [https://twitter.com/hillelogram/status/1522667509299699712?s=28&t=94aQO6N-W5F3xIX5yajuMQ](https://twitter.com/hillelogram/status/1522667509299699712?s=28&t=94aQO6N-W5F3xIX5yajuMQ)


	[Software Design](21ec4452-3375-4517-ba4f-50bcb8911091)


		**Design patterns** [kamranahmedse/design-patterns-for-humans: An ultra-simplified explanation to design patterns](https://github.com/kamranahmedse/design-patterns-for-humans)


		[https://www.infoq.com/presentations/Simple-Made-Easy/](https://www.infoq.com/presentations/Simple-Made-Easy/)


		**Write code that is easy to delete, not easy to extend** [https://programmingisterrible.com/post/139222674273/write-code-that-is-easy-to-delete-not-easy-to](https://programmingisterrible.com/post/139222674273/write-code-that-is-easy-to-delete-not-easy-to)


		**Design Patterns explained with food** [https://github.com/wesdoyle/design-patterns-explained-with-food](https://github.com/wesdoyle/design-patterns-explained-with-food)


		**Code managment** [https://klinger.io/post/613532774806192128/code-management](https://klinger.io/post/613532774806192128/code-management)


		[tarasowski/prototype-thinking: My notes from the course](https://github.com/tarasowski/prototype-thinking)


		**Building data-centric apps with a reactive relational database** [https://riffle.systems/essays/prelude](https://riffle.systems/essays/prelude/)


		## Architecture


		[https://github.com/joelparkerhenderson/architecture_decision_record#what-is-an-architecture-decision-record](https://github.com/joelparkerhenderson/architecture_decision_record#what-is-an-architecture-decision-record)


		[https://github.com/chanakaudaya/solutions-architecture-patterns](https://github.com/chanakaudaya/solutions-architecture-patterns)


		[https://klinger.io/post/183107642120/refactoring-larger-legacy-codebases](https://klinger.io/post/183107642120/refactoring-larger-legacy-codebases)


		Proxy: [https://www.francofernando.com/blog/distributed systems/2021-10-09-proxy-servers](https://www.francofernando.com/blog/distributed%20systems/2021-10-09-proxy-servers/)


	[Functional Programming](3f5ed5b4-4336-4554-8b2a-7d2f4e4e5570)


		### General


		[https://github.com/lucasviola/awesome-functional-programming](https://github.com/lucasviola/awesome-functional-programming)


		[https://github.com/enricopolanski/functional-programming](https://github.com/enricopolanski/functional-programming)


		**Glossary** 


		[http://degoes.net/articles/fp-glossary](http://degoes.net/articles/fp-glossary)


		[http://adit.io/posts/2013-04-17-functors,_applicatives,_and_monads_in_pictures.html](http://adit.io/posts/2013-04-17-functors,_applicatives,_and_monads_in_pictures.html)


		**Things I wish someone had explained about functional programming** [https://jrsinclair.com/articles/2019/what-i-wish-someone-had-explained-about-functional-programming/](https://jrsinclair.com/articles/2019/what-i-wish-someone-had-explained-about-functional-programming/)


		**Why**


		[http://luizsol.com/why-functional-programming](http://luizsol.com/why-functional-programming/)


		[https://functional.christmas/2020](https://functional.christmas/2020)


		[https://bartoszmilewski.com/2021/02/16/functorio/](https://bartoszmilewski.com/2021/02/16/functorio/)


		---


		[ADTs](5a37cbde-c30f-4354-9762-9450f462fe02)


			**Introduction**


			[https://jnkr.tech/blog/church-encodings-of-simple-adts](https://jnkr.tech/blog/church-encodings-of-simple-adts)


			[https://jnkr.tech/blog/introduction-to-algebraic-data-types](https://jnkr.tech/blog/introduction-to-algebraic-data-types)


		[GADT](afd1f78d-82ce-4ae0-acc7-ebface198d4b)


			GADT
			[https://sketch.sh/s/yH0MJiujNSiofDWOU85loX/](https://sketch.sh/s/yH0MJiujNSiofDWOU85loX/)


			
			Phantom Types
			[https://gist.github.com/busypeoples/3a28d039272ec3eb33ca2fc6b32dafc7](https://gist.github.com/busypeoples/3a28d039272ec3eb33ca2fc6b32dafc7)


			[https://gabriel.radanne.net/papers/gadts.pdf](https://gabriel.radanne.net/papers/gadts.pdf)


		[Lambda calculus](d6215967-6849-491b-a581-17263a071d36)


			[https://www.youtube.com/watch?v=3VQ382QG-y4](https://www.youtube.com/watch?v=3VQ382QG-y4)


			[https://www.youtube.com/watch?v=pAnLQ9jwN-E](https://www.youtube.com/watch?v=pAnLQ9jwN-E)


			[https://dkeenan.com/Lambda/](https://dkeenan.com/Lambda/)


			[https://mvanier.livejournal.com/2897.html](https://mvanier.livejournal.com/2897.html)


			Combinators


			Let's start with what a combinator is. In short, it's a function that _only_ uses its parameters, and nothing else – i.e. no "free" variables. Some examples:


			```plain text
			λ x . x            -- I  / identity
			λ a b . a          -- K  / first / const
			λ a b . b          -- KI / second
			λ f a b . f b a    -- C  / flip
			λ f g a . f (g a)  -- B  / composition
			
			```


			And some counter-examples:


			```plain text
			λ f . f x          -- where does x come from?
			λ f a . f (g a)    -- where does g come from?
			λ n . 1 + n        -- where do 1 and + come from?
			λ x . (x, x)       -- where does the tuple constructor (,) come from?
			
			```


			A combinator can basically only "remix" its arguments via function application and grouping (parens).


			The Y Combinator


			The Setup: Trying to Recurse Without Names


			You may have noticed that many combinators have traditional names from mathematics, such as the I, K, C, and B combinators above. The Y combinator is another example.


			In the lambda calculus, there are only anonymous functions defined via `λ`. We as readers might assign them names such as "identity" or "I" or "flip" or "C", but that is _not part of the actual language_. So a question arises: can we not make recursive functions? After all, to be recursive, a function needs to refer to _itself_, and the way we _normally_ do that is to use a name:


			```plain text
			factorial n =
			    if   n > 0
			    then n * (factorial (n -1))
			    else 1
			
			```


			Without names though, it first _seems_ like recursion must be impossible:


			```plain text
			λ n .
			    if   n > 0
			    then n * (????)
			    else 1
			
			```


			You can start to try to fill in the `????` with `λ n . if n > 0 then n * (????)` but merely _writing down_ this recursive definition by supplying the definition over and over is itself an infinite loop! You'd be nesting the definition within itself forever.


			The Solution: The Y Combinator


			However, it _is_ possible in lambda calculus to create a recursive function by starting with a function that is _almost_ (but not actually) recursive, and to feed this "pseudorecursive" function to a helper which "wires up" the recursion for you, creating a _truly_ recursive function. This helper is called a _fixed point combinator_, and one example is Haskell Curry's famous **Y combinator**. It looks like this:


			```plain text
			λ f . (λ x . f (x x)) (λ x . f (x x))
			
			```


			At first glance it's not at all obvious what this does or why it's important. It's confusing to even start tracing the internal logic; given some `f`, it calls a function `(λ x . f (x x))` on… that same function? Which means `x` is `(λ x . f (x x))`, but we pass that _to_ `f` in the body, but applied to… itself? But when we apply it to itself… wait, where were we? There's quite a lot of things getting applied to themselves and passed into things that apply things to themselves, here! And that maybe is a clue that this spaghetti can maybe do something fancy with respect to wiring up functions to call themselves.


			Let's take our recursive named fibonacci function:


			```plain text
			factorial n =
			    if   n > 0
			    then n * (factorial (n -1))
			    else 1
			
			```


			Remember, this isn't legal lambda calc. Even if we use names like `factorial` as a human-friendly shorthand for reading & writing lambda calc, the actual language doesn't have them, so a function cannot actually directly refer to itself. So instead, we are going to make a very small change, and say that instead of factorial calling _itself_, it will call some _passed-in_ function to perform the next step:


			```plain text
			pseudoFactorial f n =
			    if   n > 0
			    then n * (f (n -1))
			    else 1
			
			```


			Interesting! This is no longer recursive: `pseudoFactorial` never refers to `pseudoFactorial`. So if we can somehow pass in this _same logic_ (if n > 0, etc.) as `f`, then we will have a truly recursive factorial function!


			That's what Y does:


			```plain text
			(λ f . (λ x . f (x x)) (λ x . f (x x)))
			(λ f n . if   n > 0 then n * (f (n -1)) else 1)
			
			```


			Above, we are applying the Y combinator (`(λ f . (λ x ....)`) to our pseudo-recursive factorial function (`(λ f n . if...`). The _result_ of using our helper function Y on our not-quite-recursive pseudoFactorial function is the recursive function `factorial`:


			```plain text
			factorial = λ n . if (n > 0) then n * (factorial (n - 1)) else 1)
			
			```


			How can this even work?


			This seems almost magical. How does Y turn a non-recursive function into a recursive one, without using names? The mechanical steps have been traced out in many places, e.g. you can follow the beta-reduction yourself or on Wikipedia or Stack Overflow or wherever, but the intuition is this: `Y f = f (Y f)`. So `Y` takes out pseudo-recursive function `λ f n . ... f(something) ...` and turns it into `λ n . ... (Y f)(something) ...`. But since `Y f` _IS_ `λ n . ... (Y f)(something) ...`, we are passing the same function _into itself_ as an argument, so we can re-use its logic!


			Do I need this?


			No. Not as a beginner.


			This exists almost entirely as a beautiful mathematical truth, that makes the pure lambda calculus turing-complete, equivalent to Turing Machines and Recursive Function Theory.


			Functional languages like Haskell are not only lambda calculus, and _do_ support using names to define recursive functions. You can happily define `factorial n = if n > 0 then n * (fact $ n - 1) else 1` in Haskell, with no Y combinator in sight.


			There _are_ some clever uses for fixed-point combinators in programming. For example, when memoizing recursive functions in JavaScript, a naive memoization using a helper like `memoize` which takes an arbitrary function `f` and wraps it, caches only the final answer from a recursive call like `factorial(30)` and not each sub-step. To memoize sub-steps, one usually has to modify the body of the function itself, which means you can no longer just chuck functions into some `memoize` helper to do it for you. However, using a fixed-point combinator, you can make "recursion decorators" which apply some sort of effect to each recursive step of any "pseudorecursive" function. You still need to write your recursive functions in this alternative pseudorecursive form, taking an extra `step` or `f` param, but you don't need to implement the memoization directly.


			However, _even in those clever cases_, you STILL don't usually need the bona-fide Y combinator: JS also supports named recursion, so you can implement a fixed point combinator using `function Y(f) = f(Y(f))`. Since JS is eager instead of lazy, you'll actually need to use some kind of thunked version like `function Z(f) = f(() => Z(f))`, but that's just a small implementation wrinkle.


			I have never seen the bona fide pure lambda calculus Y combinator used in a practical program, even if I have sometimes seen fixed points used in very clever code. So if all this feels a bit much… don't worry about it! It's a cool and wonderful mathematical star which you can safely ignore as a programmer.


		[Polymorphic type constraints | CraigFe](d1ded3a8-18d1-4a5b-9759-da7739b2fe06)


			[https://www.craigfe.io/posts/polymorphic-type-constraints](https://www.craigfe.io/posts/polymorphic-type-constraints)


			One of the earliest lessons of any functional programming tutorial is how to write polymorphic functions and their signatures:


			A typical explanation of these type signatures goes along the lines of:


			As is often the case with introductory explanations, this is _just_ specific enough to be technically correct without introducing too many new concepts, letting us hurry on to demonstrating useful examples before the student gets bored. Unfortunately, we've laid a trap: when our reader learns about type constraints, they naturally try to combine these two "intuitive" features and get bitten:


			In this case, the student finds that `'a -> 'a` is a valid constraint for a function of type `int -> int`, and their mental model is broken almost immediately. It's quite natural to expect `id2` to be rejected as a non-polymorphic function, particularly given our vague explanation of what `'a` actually means.


			Our hypothetical student's mistake stems from the fact that type variables in signatures are implicitly _universally-quantified_ – that is, they stand for _all_ types – whereas type variables in constraints are not. To understand what this means, let's try to pin down a more precise idea of what type variables _are_. If you're already indoctrinated comfortable with type variables, you may wish to [cut to the chase](https://www.craigfe.io/posts/polymorphic-type-constraints).


			## What is a type variable anyway?


			Type variables in constraints are referred to as being "unbound" (or "free"), meaning that they stand for _some_ type that is not yet known to the type-checker: they are placeholders that can later be filled by a particular type. Without going into [the details](http://dev.stephendiehl.com/fun/006_hindley_milner.html), these placeholders are gradually determined as the type-checker resolves constraints. For instance, in our `id2` example, the type-checker decides that `'a` equals `int` by first reconciling the user-supplied constraint `'a -> 'a` with the constraint `int -> int` that it inferred from the implementation.


			To a theorist (or type-system developer), who regularly has to worry about types that are not yet fully known, the notion of a "placeholder" is a sensible default meaning of an unbound type variable. Such people also tend to use explicit syntax to disambiguate the alternative case, type variables that _are_ bound:


			We call "`∀ a`" a _universal quantifier_ because it introduces a variable `a`, bound inside the quantifier, that can stand for any type in the universe of OCaml types. It's this flavour of type variable that enables parametric polymorphism and – although the OCaml syntax often tries to hide it from you – these quantifiers exist everywhere in your programs. As I already mentioned, all unbound variables in _signatures_ are implicitly quantified in this way:


			On the implementation side of `length`, the compiler will check to see if there are any placeholder variables left after type-checking the definition and wrap them in universal quantifiers (if it's sure that it's safe to do so[2](https://www.craigfe.io/posts/polymorphic-type-constraints)). When this happens, we say that those type variables have been _generalised_. Once `length` has been given its polymorphic type, the user gets to pick a specific type `a` at each call-site by passing it a list of any element type they want. This idea of choosing the instantiation of `a` at each call-site is what is "parametric" about "parametric polymorphism".


			Taking a step back, we can now see what went wrong with our hypothetical introduction to type variables above: it led our student to think of all type variables as being implicitly universally-quantified, when this is not true in constraints[3](https://www.craigfe.io/posts/polymorphic-type-constraints). So, given that we can't rely on implicit generalisation in constraints, what _can_ we do to declare that our code is polymorphic within the implementation itself?


			The punchline is that OCaml actually _does_ have syntax for expressing polymorphic constraints – and it even involves an explicit quantifier – but sadly it's not often taught to beginners:


			The syntax `'a. 'a -> 'a` denotes an [explicitly-polymorphic type](https://caml.inria.fr/pub/docs/manual-ocaml/types.html#poly-typexpr), where `'a.` corresponds directly with the `∀ a.` quantifier we've been using so far. Applying it here gives us a satisfyingly readable error message:


			The caveat of polymorphic constraints is that we can only apply them directly to `let`bindings, not to function bodies or other forms of expression:


			This somewhat unhelpful error message arises because OCaml will never infer a polymorphic type for a value that is not `let`bound. Trying to make your type inference algorithm cleverer than this quickly runs into certain [undecidable problems](https://www.microsoft.com/en-us/research/wp-content/uploads/2016/02/putting.pdf); the parser knows that the type-checker is afraid of undecidable problems, and so rejects the program straight away[4](https://www.craigfe.io/posts/polymorphic-type-constraints).


			In spite of their limitations, explicitly-polymorphic type constraints are a great way to express polymorphic intent in your OCaml programs, either as internal documentation or to have more productive conversations with the type-checker when debugging. I recommend using them frequently and teaching them to beginners as soon as possible.


			At this point, if you suffered through my explanation of type variables in the previous section, you may be thinking the following:


			Personally, I find that introducing these terms early on in the learning process is easily worthwhile in avoiding early roadblocks, but that discussion can wait for another time. In the spirit of functional programming for the masses, let's summarise with a less jargon-heavy attempt at redrafting our hypothetical education resource:


			The explanation is undeniably still longer and more technical than the one we started with, but crucially it uses the extra space to give the reader a clue as to how to debug their polymorphic functions.


			The story doesn't end here. We haven't discussed [existential quantifiers](https://caml.inria.fr/pub/docs/manual-ocaml/gadts.html), the other type of type variable binding; or [polymorphic recursion](https://caml.inria.fr/pub/docs/manual-ocaml/polymorphism.html#s:polymorphic-recursion), where polymorphic annotations become compulsory; or [locally-abstract types](https://caml.inria.fr/pub/docs/manual-ocaml/locallyabstract.html), which offer other useful syntaxes for constraining your OCaml programs to be polymorphic. These will all have to wait for future posts. For now, thanks for reading!


		[Types](6ec05701-a861-4125-a080-34a439a041e6)


			[https://stackoverflow.com/questions/12532552/what-part-of-hindley-milner-do-you-not-understand](https://stackoverflow.com/questions/12532552/what-part-of-hindley-milner-do-you-not-understand)


			[https://plfa.github.io/](https://plfa.github.io/)


		[Path to Type Theory](d3a90a63-e07a-43d5-8bb7-2ae9fa3bb2a0)


			# Discrete Math & TCS

			- Formal Language
			- Chomsky Hierarchy
			- Deductive Systems

			## Computation

			- Rewriting System (_h level 1)_
			- Proof Search

			# Constructions from Set Theory

			- Model Theory
			- Universal Algebra
			- Numbers from sets (natural, integers, rational, real from dedekind cuts, etc)

			## Algebraic Structures

			- Order Theory
			- Group Theory
			- Ring, Field, Modules; **Galois Theory**
			- Lattices, Heyting, Boolean Algebra
			- Vector Spaces

			## Subset Structures

			- Topology
			- Manifolds, Homotopy
			- Sigma Algebra, Metric Space

			## Byproducts of Math Fields

			- Probability & Statistics from Sigma Algebra
			- Linear Algebra from Vector Spaces
			- Analysis from topology & Bishop constructive analysis

			# Mathematical Philosophy & Foundations

			- Russel Paradox
			- Godel Incompleteness

			## Philosophies

			- Platonism
			- Logicism
			- Formalism
			- Intuitionism

			# Category Theory


			_(h level 3)_


			## Small Categories


			### Definitions

			- Morphism
			- Functors
			- Natural Transformation

			### Universal Propery Structures

			- Limits
			- Co - ; colimits, initial object, ...
			- Terminal Objects
			- Product
			- Pullback
			- Equalizer

			### Category Properties

			- Monoidal
			- Symmetric
			- Cartesian
			- Closed

			### Functors

			- Profunctor
			- Contravariant
			- Presheaf

			### Natural Transformation


			## Higher Categories

			- Topos Theory _(h level infinity)_
			- ??
			- Can model algebraic geometry

			# Type Theory


			## Proof Calculi


			_(h level 1)_

			- Hilbert system
			- Natural Deduction
			- Gentzen; Sequent Calculi

			## Logic

			- Intuitionistic Logic
			- Constructive Mathematics
			- Combinatory Logic

			## Lambda Calculus

			- As a programming language
			- As a type theory
			- Lambda cube

			## Martin Löf Type Theory

			- Able to express Bishops Constructive Analysis

			### Curry Howard Lambek Isomorphism

			- As logic
			- As homotopy
			- As weak infinity groupoids
			- As (infinity, 1) category
			- As infinity-topos

			### Other Models of Types

			- Cartesian Closed Category
			- Simplicial Sets
			- Chain Complex
			- Linear Logic

			# Homotopy Type Theory


			Univalence Axiom


			## Models

			- Kan Simplicial set l
			- Quillen Model Category
			- Weak Factorization System

			## Constructive Univalence

			- Bezem-Coquand-Huber (presheaves on symmetric monoidal group category)
			- Cohen-Coquand-Huber-Moertberg / Cubical (+diagnoals, cartesian cube category)

		**Category Theory**

		- [https://boris-marinov.github.io/category-theory-illustrated](https://boris-marinov.github.io/category-theory-illustrated/)
		- [https://github.com/prathyvsh/category-theory-resources](https://github.com/prathyvsh/category-theory-resources)

		**Lamda calculus**


		[image](https://s3.us-west-2.amazonaws.com/secure.notion-static.com/67700759-312e-46b0-a644-fe8180d9ee63/lambdanotes.pdf?X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Content-Sha256=UNSIGNED-PAYLOAD&X-Amz-Credential=AKIAT73L2G45EIPT3X45%2F20220725%2Fus-west-2%2Fs3%2Faws4_request&X-Amz-Date=20220725T091358Z&X-Amz-Expires=3600&X-Amz-Signature=282e04bb19928d0e306ca36983b0d29df40b047b97f746c75bb4d9b28fde5581&X-Amz-SignedHeaders=host&x-id=GetObject)


		**Patterns**
		[https://sporto.github.io/elm-patterns](https://sporto.github.io/elm-patterns)


		**Thinking what's a function**


		[https://gist.github.com/mbilokonsky/9445e2e8da0f66aee7d1c8ab0cfd4415](https://gist.github.com/mbilokonsky/9445e2e8da0f66aee7d1c8ab0cfd4415)


		**Lenses**


		Theory and Applications of Lenses and Optics [https://github.com/bgavran/Lens_Resources](https://github.com/bgavran/Lens_Resources)


		Algebraic Lenses [https://chrispenner.ca/posts/algebraic](https://chrispenner.ca/posts/algebraic)


		**Applicatives**


		[https://andywhite.xyz/posts/2019-11-07-a-laymans-guide-to-applicatives-in-reasonml](https://andywhite.xyz/posts/2019-11-07-a-laymans-guide-to-applicatives-in-reasonml/)


		**Functors**


		[https://andywhite.xyz/posts/2019-11-01-a-laymans-guide-to-functors-in-reasonml](https://andywhite.xyz/posts/2019-11-01-a-laymans-guide-to-functors-in-reasonml/)


		**Type-classes**


		[https://medium.com/@terezk_a/haskell-in-elm-terms-type-classes-415f1612b335](https://medium.com/@terezk_a/haskell-in-elm-terms-type-classes-415f1612b335)


		---


		## Articles


		**From dynamic to static typing in three steps**


		[https://dev.to/lucamug/three-steps-4n7](https://dev.to/lucamug/three-steps-4n7)


		[https://blog.noredink.com/post/658510851000713216/haskell-for-the-elm-enthusiast](https://blog.noredink.com/post/658510851000713216/haskell-for-the-elm-enthusiast)


		CODE IS ENGINEERING, TYPES ARE SCIENCE - [https://www.tweag.io/posts/2020-03-05-peirce.html](https://www.tweag.io/posts/2020-03-05-peirce.html)


		Intro to Idris typed-driven development [https://juliu.is/peeling-zeroes](https://juliu.is/peeling-zeroes/)


	[Compilers](8c3f0e69-f585-4dd0-9d56-d86788e20049)


		**Demystifying interpreters: A friendly introduction on what's and how's** [https://rena.to/blog/demystifying-interpreters](https://rena.to/blog/demystifying-interpreters)


		**This is an ultra-simplified example of all the major pieces of a modern compiler written in JavaScript**
		[https://github.com/jamiebuilds/the-super-tiny-compiler](https://github.com/jamiebuilds/the-super-tiny-compiler)


		**A guided handbook on how to use Babel and how to create plugins for Babel.** [https://github.com/jamiebuilds/babel-handbook](https://github.com/jamiebuilds/babel-handbook)


		[https://borretti.me/article/lessons-writing-compiler](https://borretti.me/article/lessons-writing-compiler)


		[http://cmsc-28000.cs.uchicago.edu/2018-spring/lectures.php](http://cmsc-28000.cs.uchicago.edu/2018-spring/lectures.php)


		**LL and LR grammars**


		[https://cs.stackexchange.com/questions/43/language-theoretic-comparison-of-ll-and-lr-grammars/48#48](https://cs.stackexchange.com/questions/43/language-theoretic-comparison-of-ll-and-lr-grammars/48#48)


		**Parser combinator** [https://reasonml.chat/t/a-gentle-introduction-to-parser-combinators-and-angstrom/2546](https://reasonml.chat/t/a-gentle-introduction-to-parser-combinators-and-angstrom/2546)


		
		**How I wrote my own "proper" programming language** [https://mukulrathi.com/create-your-own-programming-language/intro-to-compiler](https://mukulrathi.com/create-your-own-programming-language/intro-to-compiler/)


	[Terminal](85141829-c970-42cd-a272-97277295c360)


		**CLIs**


		Command Line Interface Guidelines [https://clig.dev](https://clig.dev/)


		[https://github.com/jlevy/the-art-of-command-line/blob/master/README.md](https://github.com/jlevy/the-art-of-command-line/blob/master/README.md)


		**Bash**


		[denysdovhan/bash-handbook: For those who wanna learn Bash](https://github.com/denysdovhan/bash-handbook)


		**vim**


		[https://learnbyexample.github.io/vim_reference/Introduction.html](https://learnbyexample.github.io/vim_reference/Introduction.html)


		**awk**


		[https://ferd.ca/awk-in-20-minutes.html](https://ferd.ca/awk-in-20-minutes.html)


		[https://earthly.dev/blog/awk-examples](https://earthly.dev/blog/awk-examples/)


		**set**


		[https://pubs.opengroup.org/onlinepubs/9699919799.2018edition/utilities/V3_chap02.html#set](https://pubs.opengroup.org/onlinepubs/9699919799.2018edition/utilities/V3_chap02.html#set)


		**makefile**


		[https://alextan.medium.com/makefile-101-56ba4590025b](https://alextan.medium.com/makefile-101-56ba4590025b)


		[https://gist.github.com/isaacs/62a2d1825d04437c6f08](https://gist.github.com/isaacs/62a2d1825d04437c6f08)


		[https://tech.davis-hansson.com/p/make/](https://tech.davis-hansson.com/p/make/)


		[https://opensource.com/article/18/8/what-how-makefile](https://opensource.com/article/18/8/what-how-makefile)


		[https://www.cprogramming.com/tutorial/makefiles_continued.html](https://www.cprogramming.com/tutorial/makefiles_continued.html)


		**jq**


		---


		rust-alternatives to basic CLIs


		man pages


		explain commands and flags


	[regex](569407ef-29cd-4f18-bd6a-aca8c3e829b6)


		[Rubular: a Ruby regular expression editor and tester](http://rubular.com/)


		[RegExr: Learn, Build, & Test RegEx](http://www.regexr.com/)


		[PHP Live Regex](http://www.phpliveregex.com/)


		[Regular Expressions - JavaScript | MDN](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Guide/Regular_Expressions?redirectlocale=en-US&redirectslug=JavaScript%2FGuide%2FRegular_Expressions)


		[Online regex tester and debugger: JavaScript, Python, PHP, and PCRE](http://regex101.com/)


	[Git](ae9d6f0a-02ae-4575-af87-edd4b422d405)


		Tips [https://github.com/git-tips/tips](https://github.com/git-tips/tips)


		[Oh Shit, Git!?!](https://ohshitgit.com/)


		Rebase / Merge [https://css-tricks.com/rebase-vs-merge-integrating-changes-in-git/](https://css-tricks.com/rebase-vs-merge-integrating-changes-in-git/)


	[Computer Science](520df7c1-0507-4800-a980-003a71279e84)


		**Teach Yourself Computer Science** [https://teachyourselfcs.com/](https://teachyourselfcs.com/)


		**How do arrays work?** [https://www.nan.fyi/how-arrays-work](https://www.nan.fyi/how-arrays-work)


		**A collection of full-stack resources for programmers** [https://github.com/charlax/professional-programming](https://github.com/charlax/professional-programming)


		**Unicodes** [https://www.joelonsoftware.com/2003/10/08/the-absolute-minimum-every-software-developer-absolutely-positively-must-know-about-unicode-and-character-sets-no-excuses/](https://www.joelonsoftware.com/2003/10/08/the-absolute-minimum-every-software-developer-absolutely-positively-must-know-about-unicode-and-character-sets-no-excuses/)


		**ASCII** [https://www.youtube.com/watch?v=B1Sf1IhA0j4](https://www.youtube.com/watch?v=B1Sf1IhA0j4&ab_channel=dizauvi)


		**UTF-8** [https://www.youtube.com/watch?v=vLBtrd9Ar28](https://www.youtube.com/watch?v=vLBtrd9Ar28&ab_channel=dizauvi)


		[https://philna.sh/blog/2020/03/04/mistakes-treating-paths-as-strings/](https://philna.sh/blog/2020/03/04/mistakes-treating-paths-as-strings/)


	[Frontend](5c661345-9d22-493d-941e-2fb9a24ccd25)


		[Performance](b9106867-6805-40eb-9441-edb3bd2a2ced)


			[WebPagetest - Website Performance and Optimization Test](http://www.webpagetest.org/)


			[Website speed test](http://tools.pingdom.com/fpt/)


			Nice Performance study [https://threader.app/thread/1275769142809944064](https://threader.app/thread/1275769142809944064)


		[CSS](b032379a-fae0-4e72-8ac9-4af5ddab1189)


			[Learn CSS Layout](http://learnlayout.com/)


			**Grid** [https://twitter.com/prathkum/status/1518162718213160960?s=28&t=VHTHoZ_TUmEP_iQ1viEqfQ](https://twitter.com/prathkum/status/1518162718213160960?s=28&t=VHTHoZ_TUmEP_iQ1viEqfQ)


			### Tools


			[CSS Triggers](http://csstriggers.com/)


			[CSS Stats](http://cssstats.com/)


			[Sassisfaction :: Awesome Sass Resources](http://sassisfaction.com/)


			[CSS Shorthand Generator](http://shrthnd.volume7.io/)


			[SassMeister | The Sass Playground!](http://sassmeister.com/)


			[CSS3 PIE: CSS3 decorations for IE](http://css3pie.com/)


			[CSS3Ps - free cloud based photoshop plugin that converts layers to CSS3 styles.](http://css3ps.com/)


			[CSSDeck](http://cssdeck.com/)


			[Pens picked by the Editors of CodePen](http://codepen.io/)


			[Keyframer](http://alexberg.in/keyframer/)


			[HTML5 Online Animation Editor | Animatron](http://animatron.com/)


			[cssmatic](http://www.cssmatic.com/)


			[IcoMoon App - Icon Font, SVG, PDF & PNG Generator](https://icomoon.io/app/#/select)


			[Tridiv](http://tridiv.com/app/index.html?dmlldz1lZGl0b3ImZG9jPXsic2V0dGluZ3MiOnsibmFtZSI6IlVudGl0bGVkIERvY3VtZW50IiwibGlnaHQiOiJzdGF0aWMiLCJzaGFkZSI6Ii4zIiwidGludCI6Ii4xNSIsImJvcmRlciI6IjAuNCIsImJnIjoidHJhbnNwYXJlbnQiLCJzbmFwIjoib2ZmIiwibWF0Y2giOjAuNSwiem9vbSI6MTAwfSwic2hhcGVzIjpbXX0=)


			[Tools](https://coveloping.com/tools)


			[Ceaser - CSS Easing Animation Tool - Matthew Lein](http://matthewlein.com/ceaser/)


			[Magic Animations CSS3](http://www.minimamente.com/example/magic_animations/)


			[Flexplorer](http://bennettfeely.com/flexplorer/)


			[Grid.Guide — Pixel Perfect Grids](http://grid.guide/)


			[logeshpaul/CSS-Hacks: Collection of CSS Hacks collected overtime to get your layout right across browsers!](https://github.com/logeshpaul/CSS-Hacks)


			### Inspiration


			[Hakim El Hattab](http://hakim.se/)


			[CSS Gallery - Web design inspiration - CssDsgn](http://www.cssdsgn.com/)


			[CSSline - Showcase gallery of excellent CSS sites.](http://cssline.com/)


			[CSS Animation](https://cssanimation.rocks/)


			[CSS Triggers...](http://csstriggers.com/)


			Website Style Guide Resources [Website Style Guide Resources](http://styleguides.io/)


			### Articles


			[How to Center in CSS](http://howtocenterincss.com/)


			[Sass functions cheat sheet](https://gist.github.com/AllThingsSmitty/3bcc79da563df756be46)


			[Cross-Browser Inline-Block | Mozilla Web Development](https://blog.mozilla.org/webdev/2009/02/20/cross-browser-inline-block/)


			[vasanthk/css-refresher-notes](https://github.com/vasanthk/css-refresher-notes)


			[vasanthk/browser-rendering-optimization](https://github.com/vasanthk/browser-rendering-optimization)


			[logeshpaul/CSS-Hacks: Collection of CSS Hacks collected overtime to get your layout right across browsers!](https://github.com/logeshpaul/CSS-Hacks)


			[CSS Reference | Codrops](http://tympanus.net/codrops/css_reference/)


			[What No One Told You About Z-Index — Philip Walton](http://philipwalton.com/articles/what-no-one-told-you-about-z-index/)


			[CSS Guidelines (2.1.4) – High-level advice and guidelines for writing sane, manageable, scalable CSS](http://cssguidelin.es/)


			[Code Guide by @mdo](http://mdo.github.io/code-guide/)


			[Table Styling — Potion — Magic of CSS — Adam Schwartz](http://adamschwartz.co/magic-of-css/potions/table-styling/)


			[Flexbox Cheatsheet Cheatsheet](http://jonibologna.com/flexbox-cheatsheet/)


			[Collection of Learning Flexbox Resources](http://designposts.net/collection-of-learning-flexbox-resources/)


			[From Novice to Expert: The Ultimate list of CSS3 Resources, Tutorials, Tips and More](http://www.simplilearn.com/css3-resources-ultimate-list-article)


			[What The FlexBox?!](http://flexbox.io/#/)


			[A Complete Guide to Flexbox | CSS-Tricks](https://css-tricks.com/snippets/css/a-guide-to-flexbox/)


			Defensive CSS [https://ishadeed.com/article/defensive-css](https://ishadeed.com/article/defensive-css/)


			Incomplete List of Mistakes in the Design of CSS [https://wiki.csswg.org/ideas/mistakes](https://wiki.csswg.org/ideas/mistakes)


		[RxJS](b3f107b4-9ef6-470d-a17d-2121206512a4)


			[RxMarbles: Interactive diagrams of Rx Observables](http://rxmarbles.com/)


			[Introduction | RxJS - Javascript library for functional reactive programming.](http://xgrommx.github.io/rx-book/index.html)


			[Presentations | RxJS - Javascript library for functional reactive programming.](http://xgrommx.github.io/rx-book/content/resources/presentations/index.html)


			[Reactive-Extensions/RxJS · Design Guidelines](https://github.com/Reactive-Extensions/RxJS/tree/master/doc/designguidelines)


			[Reactive-Extensions/RxJS](https://github.com/Reactive-Extensions/RxJS)


			[RxJs Testing in real world applications](https://blog.hyphe.me/rxjs-testing-in-real-world-applications/)


			[Testing reactive code | Better world by better software](https://glebbahmutov.com/blog/testing-reactive-code/)


			[Matthew Podwysocki: "Reactive JavaScript at Netflix, Microsoft and the World" - YouTube](https://www.youtube.com/watch?v=eaap06m2Iqw&feature=youtu.be)


			[awesome-reactive-programming/README.md at master · xgrommx/awesome-reactive-programming](https://github.com/xgrommx/awesome-reactive-programming/blob/master/libraries/rx/react/README.md)


			[stomita/rxdux: Yet another flux implementation based on redux, extending reducer to allow asynchronous state change](https://github.com/stomita/rxdux)


			[TSERS](https://github.com/tsers-js)


			
			**The introduction to Reactive Programming you've been missing** [https://gist.github.com/868e7e9bc2a7b8c1f754](https://gist.github.com/868e7e9bc2a7b8c1f754)


		[React](6250aa2b-7baa-43d1-b08c-35ddf222dbf5)


			**Inspiration from XHP** [https://codebeforethehorse.tumblr.com/post/3096387855/an-introduction-to-xhp](https://codebeforethehorse.tumblr.com/post/3096387855/an-introduction-to-xhp)


			[https://github.com/hhvm/xhp-lib](https://github.com/hhvm/xhp-lib)


			[https://github.com/facebookarchive/xhp-php5-extension](https://github.com/facebookarchive/xhp-php5-extension)


			[https://github.com/phplang/xhp](https://github.com/phplang/xhp)


			[Free React and Redux Cheatsheets from @eggheadio @eggheadio](https://egghead.io/react-redux-cheatsheets?utm_content=buffercd40c&utm_medium=social&utm_source=twitter.com&utm_campaign=buffer)


			[React.js cheatsheet](http://ricostacruz.com/cheatsheets/react.html)


			[React.js Conf 2015 - Making your app fast with high-performance components - YouTube](https://www.youtube.com/watch?v=KYzlpRvWZ6c)


			[react-howto](https://github.com/petehunt/react-howto)


			[https://github.com/mithi/react-philosophies](https://github.com/mithi/react-philosophies)


			[EvanBacon/AWESOME-REACT-NATIVE-WEB: 💙 React Native Web patterns, techniques, tips, and tricks ✨](https://github.com/EvanBacon/AWESOME-REACT-NATIVE-WEB)


			[Components](a7286bfc-3d3e-4f8c-8335-df25df352f6a)


				[https://www.downshift-js.com/](https://www.downshift-js.com/)


				[https://jquense.github.io/react-big-calendar/](https://jquense.github.io/react-big-calendar/)


				[https://react-select.com/home](https://react-select.com/home)


				[https://react-table.tanstack.com/](https://react-table.tanstack.com/)


				[https://github.com/Hacker0x01/react-datepicker](https://github.com/Hacker0x01/react-datepicker)


				[https://github.com/henrykuzmick/react-skeleton-loader#readme](https://github.com/henrykuzmick/react-skeleton-loader#readme)


				[https://reactour.js.org/](https://reactour.js.org/)


				[https://react-spectrum.adobe.com/react-aria/](https://react-spectrum.adobe.com/react-aria/)


				[https://github.com/tailwindlabs/headlessui/tree/develop/packages/%40headlessui-react](https://github.com/tailwindlabs/headlessui/tree/develop/packages/%40headlessui-react)


		[React Native](34d65b72-4f4c-44d6-baa4-d41073d4f3f4)


			[https://github.com/wix/react-native-ui-lib](https://github.com/wix/react-native-ui-lib)


			[https://github.com/nandorojo/dripsy](https://github.com/nandorojo/dripsy)


			[https://callstack.github.io/react-native-paper/](https://callstack.github.io/react-native-paper/)


			[https://github.com/react-native-elements/react-native-elements](https://github.com/react-native-elements/react-native-elements)


		[Redux](627a98c6-7fbd-43fc-badb-7f2b26ce5e5e)


			[Full-Stack Redux Tutorial](http://teropa.info/blog/2015/09/10/full-stack-redux-tutorial.html)


			[Redux best practices — Lexical Labs Engineering — Medium](https://medium.com/lexical-labs-engineering/redux-best-practices-64d59775802e#.pgd2mxaza)


			[markerikson/react-redux-links: Curated links I've collected on React, Redux, ES6, and more](https://github.com/markerikson/react-redux-links)


			[Getting started with Redux - Example application | jchapron](http://www.jchapron.com/2015/08/14/getting-started-with-redux/)


			[Encapsulation in Redux: the Right Way to Write Reusable Components](http://blog.javascripting.com/2016/02/02/encapsulation-in-redux/)


			[tayiorbeii/egghead.io_redux_course_notes: Notes (and partial transcription) of Dan Abramov's Redux course videos on http://egghead.io](https://github.com/tayiorbeii/egghead.io_redux_course_notes)


			[redux/FAQ.md at create-faq-page · markerikson/redux](https://github.com/markerikson/redux/blob/create-faq-page/docs/FAQ.md)


			[Understanding Redux Middleware — Medium](https://medium.com/@meagle/understanding-87566abcfb7a#.gqa9uor5h)


		[webpack](16efc165-e38b-42d5-8637-3567a84cbb24)


			[petehunt/webpack-howto](https://github.com/petehunt/webpack-howto)


			[danderu/learn-webpack: A repository with examples and exercises to learn webpack for newbies](https://github.com/danderu/learn-webpack)


		[Accessibility](023016e1-8784-47c1-a2c4-4b0807bac9f0)


			[https://www.smashingmagazine.com/2021/03/complete-guide-accessible-front-end-components](https://www.smashingmagazine.com/2021/03/complete-guide-accessible-front-end-components/)


		[http://swannodette.github.io/2013/12/17/the-future-of-javascript-mvcs/](http://swannodette.github.io/2013/12/17/the-future-of-javascript-mvcs/)


		### Utilities


		[CreateJS | A suite of JavaScript libraries and tools designed for working with HTML5](http://www.createjs.com/)


		[Js2coffee: convert JavaScript code to CoffeeScript](http://js2coffee.org/)


		[The Prettifier - Code Formatting and Syntax Highlighting](http://prettifier.net/)


		[JSDB.io - The Database of JavaScript Libraries](http://www.jsdb.io/)


		[JSON Schema Lint :: JSON Schema Validator](http://jsonschemalint.com/draft4/#)


		[RequestBin — Collect, inspect and debug HTTP requests and webhooks](http://requestb.in/)


		[Whois Lookup, Domain Availability & IP Search - DomainTools](http://whois.domaintools.com/)


		[Check Browser Compatibility, Cross Platform Browser Test - Browsershots](http://browsershots.org/)


	[Backend](69bc674e-299b-4193-afd9-ff3f66816e01)


		[Database](91b33f67-cfbb-499a-a6b3-efc9fd94caeb)


			[https://www.prisma.io/dataguide/intro](https://www.prisma.io/dataguide/intro)


			[https://evilmartians.com/chronicles/soft-deletion-with-postgresql-but-with-logic-on-the-database](https://evilmartians.com/chronicles/soft-deletion-with-postgresql-but-with-logic-on-the-database)


		[HTTP](665ac212-0f2a-4b63-bdf8-b830525d0866)


			[HTTPWTF](c511a270-afc7-4f6f-af95-dfb1e24d330f)


				# **HTTPWTF**


				HTTP is fundamental to modern development, from frontend to backend to mobile. But like any widespread mature standard, it's got some funky skeletons in the closet.


				Some of these skeletons are little-known but genuinely useful features, some of them are legacy oddities relied on by billions of connections daily, and some of them really shouldn't exist at all. Let's look behind the curtain:


				# **No-cache means "do cache"**


				Caching has never been easy, but HTTP cache headers can be particularly confusing. The worst examples of this are **`no-cache`** and **`private`**. What does the below response header do?


				**`Cache-Control: private, no-cache`**


				It looks like this means "don't store this response anywhere", right?


				_Hahaha_ no.


				In reality, this means "please store this response in all browser caches, but revalidate it when using it". In fact, this makes responses _more_ cacheable, because this applies even to responses that wouldn't normally be cacheable by default.


				Specifically, **`no-cache`** means that your content is explicitly cacheable, but whenever a browser or CDN wants to use it, they should send a request using **`If-Match`** or **`If-Modified-Since`** to ask the server whether the cache is still up to date first. Meanwhile **`private`** means that this content is cacheable, but only in end-client browsers, not CDNs or proxies.


				If you were trying to disable caching because the response contains security or privacy sensitive data that shouldn't be stored elsewhere, you're now in big trouble. In reality, you probably wanted **`no-store`**.


				If you send a response including a **`Cache-Control: no-store`** header, nobody will ever cache the response, and it'll come fresh from the server every time. The only edge case is if you send that when a client already has a cached response, which this won't remove. If you want to do that and clear existing caches too, add **`max-age=0`**.


				Twitter notably [hit this issue](https://hacks.mozilla.org/2020/04/twitter-direct-message-caching-and-firefox/). They used **`Pragma: no-cache`** (a legacy version of the same header) when they should have used **`Cache-Control: no-store`**, and accidentally persisted every user's private direct messages in their browser caches. That's not a big problem on your own computer, but if you share a computer or you use Twitter on a public computer somewhere, you've now left all your private messages conveniently unencrypted & readable on the hard drive. Oops.


				# **HTTP Trailers**


				You're probably aware of HTTP headers. An HTTP message starts with a first line that contains the method & URL (for requests) or status code & message (for responses) and then it has a series of key/value pairs for metadata, called headers, and then it has a body.


				Did you know you can also send trailers, to append metadata _after_ a message body?


				These are not widely used, but they're fully standardized and in theory everything should support them, or at least ignore them. They can be useful if you have metadata that isn't easily available initially, and you don't want need to wait for it before you send the body.


				They are used in some API protocols like gRPC, and they're primarily valuable for metadata about the overall response itself, for example you can use trailers to [include Server-Timing metadata](https://www.fastly.com/blog/supercharging-server-timing-http-trailers) to give the client performance metrics about server processing during a request, appended after the response is fully completed. They're especially useful for long responses, e.g. to include final status metadata after a long-running HTTP stream.


				It's still rare that you'll need this, but it's pretty cool that it works when you do. There's a few requirements:

				- For server response trailers, the client must advertise support for this, with a **`TE: trailers`** header on the initial request.
				- The initial headers should specify the trailer fields that will be used later, with **`Trailer: <field names>`**.
				- Some headers are never allowed as trailers, including **`Content-Length`**, **`Cache-Control`**, **`Authorization`**, **`Host`** and similar standard headers, which are often required initially to parse, authenticate or route requests.

				To send trailers in HTTP/1.1, you'll also need to use chunked encoding. HTTP/2 meanwhile uses separate frames for the body & headers, so this isn't necessary.


				A full HTTP/1.1 response with trailers might look like this:


				**`HTTP/1.1 200 OK
				Transfer-Encoding: chunked
				Trailer: My-Trailer-Field
				
				[...chunked response body...]
				
				My-Trailer-Field: some-extra-metadata`**


				# **HTTP 1XX codes**


				Did you know that an HTTP request can receive multiple response status codes? A server can send an unlimited number of 1XX codes before a final status (200, 404, or whatever it may be). These act as interim responses, and can all include their own independent headers.


				There's a few different 1XX codes available: 100, 101, 102, and 103. They're not widely used, but in some niche use cases they have some cool powers:


				# HTTP 100


				HTTP 100 is a response from a server that the request is ok _so far_, and the client should keep going.


				Most of the time, this is a no-op. If you've started sending a request, you were probably going to keep going anyway, although it's always nice to have the server's support & encouragement.


				This becomes useful though if you send a request including a **`Expect: 100-continue`** header. That header tells the server you expect a 100 response, and you're not going to send the full request body until you receive it.


				Sending **`Expect: 100-continue`** allows the server to decide if it wants to receive the whole body, which might take a lot of time/bandwidth. If the URL & headers are enough for it to already send a response (e.g. to reject a file upload) this is a quick and efficient way to do that. If the server does want to receive the full body, it sends an interim 100 response, the client continues, and then the server handles the complete request as normal when it's done.


				# HTTP 101


				HTTP 101 is used to switch protocols. It says "I've sent you a URL and headers, and now I want to do something _completely different_ with this connection". Not just a different request, but different protocol entirely.


				The main use case is to set up a websocket. To do so, the client sends a request including these two headers:


				**`Connection: upgrade
				Upgrade: websocket`**


				Then, if the server accepts, it sends a response like:


				**`HTTP/1.1 101 Switching Protocols
				Upgrade: websocket
				Connection: Upgrade`**


				And then from there they stop speaking HTTP, and start exchanging raw websocket data on this connection instead.


				This status is also used to upgrade from HTTP/1.1 to HTTP/2 on the same connection, and you could use it to transform HTTP connections into all sorts of other TCP-based protocols too.


				That said, this status _isn't_ supported in HTTP/2, which uses a different mechanism for protocol negotiation and a [totally different mechanism](https://tools.ietf.org/html/rfc8441) to set up websockets (which basically isn't supported anywhere - websockets are always HTTP/1.1 right now).


				# HTTP 102


				HTTP 102 tells the client that the server is still processing the request, and it'll respond _soon_. This differs from 100 in that the whole request has now been received, and all the action is now happening on the server side, with the client just waiting.


				This isn't much used as far as I can tell, and it seems to mainly exist as a keep-alive, to make sure the client doesn't think the server has simply died. It's in the original HTTP specifications, but it's been removed from many new editions.


				Still, it is supported & used in real places in the wild, so it's quite possible to use it in your applications if it fits your needs.


				# HTTP 103


				HTTP 103 meanwhile is a new & trendy status intended to partially replace HTTP/2's server push functionality (which is now [being removed from Chrome](https://groups.google.com/a/chromium.org/g/blink-dev/c/K3rYLvmQUBY/m/vOWBKZGoAQAJ?pli=1)).


				Using HTTP 103, a server can send some headers early, before fully handling the request and sending the rest of the response. This is primarily designed for delivering link headers, like **`Link: </style.css>; rel=preload; as=style`**, telling the client about other content that it may want to start loading early (like stylesheets, JS & images, for web page requests) in parallel with the full response.


				When the server receives a request that takes a little processing, it often can't fully send the response headers until that processing completes. HTTP 103 allows the server to immediately nudge the client to download other content in parallel, without waiting for the requested resource data to be ready.


				# **Referer**


				The HTTP Referer header tells the server which page you came from previously, or which URL triggered a resource load. This has some privacy challenges, but it's stuck around, and it's sent in most requests made as you browse the internet.


				Notably, it's spelled wrong. This was added in the very early days of the web, and the unix spell checker at the time didn't recognize either referer or referrer (the correct spelling). By the time anybody noticed, it was in serious use in infrastructure and tools all over the place, so nothing could be changed and we have to live with every browser request having a misspelled header forever.


				Not especially important unless you're writing code to read this header yourself, but a great parable for the challenges of network compatibility.


				For maximum confusion and damage potential, new privacy/security headers related to this like **`Referrer-Policy`** _do_ use the correct spelling.


				# **Websocket's 'random' UUID**


				![](https://imgs.xkcd.com/comics/random_number.png)


				_There's always_ [_a relevant XKCD_](https://xkcd.com/221/)


				We talked about how HTTP 101 requests are used to set up websockets earlier. A full request to do so might look like this:


				**`GET /chat HTTP/1.1
				Host: server.example.com
				Upgrade: websocket
				Connection: Upgrade
				Sec-WebSocket-Key: x3JJHMbDL1EzLkh9GBhXDw==
				Sec-WebSocket-Protocol: chat, superchat
				Sec-WebSocket-Version: 13
				Origin: http://example.com`**


				with a response that starts the websocket connection like this:


				**`HTTP/1.1 101 Switching Protocols
				Upgrade: websocket
				Connection: Upgrade
				Sec-WebSocket-Accept: HSmrc0sMlYUkAGmm5OPpG2HaGWk=
				Sec-WebSocket-Protocol: chat`**


				The **`Sec-WebSocket-Accept`** key here is interesting. This is designed to stop caching proxies accidentally reusing websocket responses that they don't understand, by requiring the response to include a header that matches the client header. Specifically:

				- The server receives a base64 websocket key from the client
				- The server appends the UUID **`258EAFA5-E914-47DA-95CA-C5AB0DC85B11`** to the base64 string
				- The server hashes the resulting string, encodes the hash in base64, and sends that back

				This is deeply weird. A single fixed random UUID that's used in the setup of every single websocket forever? Appending strings to base64 strings without decoding, and then base64-ing the result again too?


				The idea is that this logic isn't something that could happen by accident, or something that could ever be used elsewhere, to guarantee that both parties are intentionally starting a websocket connection. This confirms that the server or proxy isn't used cached data without understanding it, and the client hasn't been tricked into opening a websocket connection that it doesn't understand.


				This totally works, it's widely used and quick & easy to implement, which is all great, but it's wild that every websocket connection in the world relies on one magic UUID.


				# **Websockets & CORS**


				While we're talking about websockets: did you know that websockets effectively ignore all the CORS and single-origin policy restrictions that would normally apply to HTTP requests?


				CORS ensures that JavaScript running on a.com can't read data from b.com unless the latter explicitly opts into that in its response headers.


				This is important for lots of reasons, notably including network-local servers (a public web page shouldn't be able to talk to your router) and browser state (requests from one domain shouldn't be able to use cookies from another).


				Unfortunately though, websockets ignore CORS entirely, assuming instead that all websocket servers are modern & sensible enough to correctly check the **`Origin`** header for themselves. Many servers do not, and most developers I've mentioned this to weren't aware of it.


				This opens a whole world of fun vulnerabilities, nicely summarized in [this article](https://christian-schneider.net/CrossSiteWebSocketHijacking.html).


				In short: if you have a websocket API, check the **`Origin`** header and/or use CSRF tokens before trusting any incoming connections.


				# **X-* headers**


				Once upon a time (1982) [an RFC](https://tools.ietf.org/html/rfc822#section-4.7.4) suggested that using an **`X-`** prefix for message headers was a good way to differentiate custom extensions from standardized names.


				At the time this was relevant to email metadata, but this was later popularized for usage in HTTP headers too.


				This is still a common pattern, and if you look at HTTP requests as you browse the web you'll see quite a few of these:

				- **`X-Shenanigans: none`** - this appears on every response from Twilio's API. I have no idea why, but it is comforting to know there's _definitely_ no shenanigans this time round.
				- **`X-Clacks-Overhead: GNU Terry Pratchett`** - a [tribute](https://xclacksoverhead.org/home/about) to Terry Pratchett, based on the message protocols within his own books.
				- **`X-Requested-With: XMLHttpRequest`** - appended by various JS frameworks including jQuery, to clearly differentiate AJAX requests from resource requests (which can't include custom headers like this).
				- **`X-Recruiting: <cheesy pitch to get you to apply for a job>`** - quite a few companies add these as a quick way to try and hire the kind of people who read HTTP headers for fun.
				- **`X-Powered-By: <framework>`** - used to advertise the framework or technology that the server is using (usually a bad idea).
				- **`X-Http-Method-Override`** - used to set a method that couldn't be set as the real method of the request for some reason, usually a client or networking limitation. Mostly a bad idea nowadays, but still popular & supported by quite a few frameworks.
				- **`X-Forwarded-For: <ip>`** - A defacto standard used by many proxies & load balancers to include the original requester's IP in upstream requests.

				Each of these is weird and wonderful in its own way, but the pattern in general is mostly a bad idea, and a new (2011) [RFC](https://tools.ietf.org/html/draft-saintandre-xdash-00) now formally discourages its use.


				The problem is that many non-standard headers eventually do become standard. When that happens, if you used an **`X-`** prefix, now you either have to change the name (breaking all existing implementations) or standardize the **`X-`** prefix (defeating the point of the prefix entirely, and adding annoying noise to the name forever).


				This is frustrating, and it's broken some real standards:

				- Almost all web forms on the internet submit data with an unnecessarily confusing & long-winded **`Content-Type: application/x-www-form-url-encoded`** header.
				- In the [1997 RFC for HTTP](https://tools.ietf.org/html/rfc2068#section-3.5) where it defines the parsing rules for **`content-encoding`**, it requires all implementations to treat **`x-gzip`** and **`x-compress`** as equivalent to **`gzip`** and **`compress`** respectively.
				- The [standardized](https://tools.ietf.org/html/rfc7034) header for configuring web page framing is now forever **`X-Frame-Options`**, not just **`Frame-Options`**
				- Similarly, we have **`X-Content-Type-Options`**, **`X-DNS-Prefetch-Control`**, **`X-XSS-Protection`**, and various **`X-Forwarded-*`** CDN/proxy headers, all of which are widely implemented and have become either formally or defacto standard headers in widespread use.

				If you want to use a custom header, just use a custom header name that's not standardized by anybody else. If you really want to avoid collisions, consider namespacing it, but you're usually pretty safe if there's no standard header that appears after a 30 second google.


			[CORS](3be2517d-2f74-4950-91b9-1166776c16f1)


				[https://httptoolkit.tech/blog/cache-your-cors/](https://httptoolkit.tech/blog/cache-your-cors/)


				[https://httptoolkit.tech/blog/how-to-debug-cors-errors/](https://httptoolkit.tech/blog/how-to-debug-cors-errors/)


			HTTP1 → HTTP2 [https://httptoolkit.tech/blog/translating-http-2-into-http-1/](https://httptoolkit.tech/blog/translating-http-2-into-http-1/)


			[https://httptoolkit.tech/blog/http-api-problem-details/](https://httptoolkit.tech/blog/http-api-problem-details/)


		[Rest](17745409-1d6d-4aa8-aa6d-4c5af238581b)


			[Application Load Testing Tools for API Endpoints with loader.io](http://loader.io/)


			[paypal/api-standards](https://github.com/paypal/api-standards/blob/master/api-style-guide.md)


			[ProgrammableWeb - APIs, Mashups and the Web as Platform](http://www.programmableweb.com/)


			[HTTP Status Codes — httpstatus.es](http://httpstatus.es/)


			[REST API Tutorial](http://www.restapitutorial.com/)


			[API Blueprint - API Documentation with powerful tooling](https://apiblueprint.org/)


			[Apiary — Home](https://apiary.io/)


			[Error and Crash Reporting For Node.js - raygun.io](https://raygun.io/nodejs)


			[Hurl.it - Make HTTP requests](https://www.hurl.it/)


			[API Performance Monitoring · Runscope](https://www.runscope.com/)


			[Kong - Open-Source API and Microservice Management Layer](http://getkong.org/)


			[Log Management | Cloud Log Management Service | Loggly](https://www.loggly.com/)


			[Mashape - Free API Management Platform & Marketplace](https://www.mashape.com/)


		---


		[GraphQL](7627b8a9-4a48-4c77-a90a-efa743a61e98)


			What's wrong with Apollo [https://httptoolkit.tech/blog/simple-graphql-server-without-apollo/](https://httptoolkit.tech/blog/simple-graphql-server-without-apollo/)


		[Apache](bfe92624-4e09-4f8a-9d16-73c3f7032758)


			[3 Small Tweaks to make Apache fly | Server Check.in](https://servercheck.in/blog/3-small-tweaks-make-apache-fly)


			[Tune apache2 for more concurrent connections - Open-Xchange](http://oxpedia.org/wiki/index.php?title=Tune_apache2_for_more_concurrent_connections)


		[Node.js](f17d858f-17e2-484d-b855-c273ecc57fe9)


			[NODE LIST OF AWESOME](https://github.com/sindresorhus/awesome-nodejs)


			[Export This: Interface Design Patterns for Node.js Modules | Bites from Good Eggs](http://bites.goodeggs.com/posts/export-this/)


			[Node.js Hispano | Node.js – JavaScript en el Servidor – Comunidad en Español](http://www.nodehispano.com/)


			[Best Practices for Node.js Development | Heroku Dev Center](https://devcenter.heroku.com/articles/node-best-practices#specify-a-start-script)


			[Node.JS Module Patterns](http://darrenderidder.github.io/talks/ModulePatterns/#/)


			[Gentlenode | Journal](http://journal.gentlenode.com/)


			[MEAN Stack WeNode Barcelona Workshop](http://www.slideshare.net/vkarpov15/mean-stack-wenode-barcelona-workshop)


			[libs](78b2a2ab-3dfd-4d37-9c76-9fd1bd7da03b)

				- lint-staged → nano-staged
				- husky → simple-git-hooks
				- cosmiconfig → joycon
				- chalk → picocolors
				- ora → nanospinner
				- request → undici
				- express → micri
				- flat → flattie
				- Axios → Redaxios
				- husky → lefthook
				- momentjs → dayjs → date-fns
				- jest → uvu

		[laravel](235f831f-059f-48c0-a1c5-cebb2b9c0f5b)


			[FAQ — PHP-FIG](http://www.php-fig.org/faq/#what-does-fig-stand-for)


			[PHP: The Right Way](http://www.phptherightway.com/)


			[Composer, el manual oficial](http://librosweb.es/composer/)


			[Laravelista](http://laravelista.com/)


			[https://github.com/chiraggude/awesome-laravel#codebases-for-reference](https://github.com/chiraggude/awesome-laravel#codebases-for-reference)


			[Forum - Laravel.IO - The Official Laravel PHP Framework Community Portal](http://laravel.io/forum)


			[Laravel Cheat Sheet](http://cheats.jesse-obrien.ca/)


			[Packalyst :: Packages for Laravel](http://packalyst.com/)


			[Laravel en Español - Comunidad Hispanoamericana de Laravel](http://laraveles.com/foro/)


			[Tutoriales de programación web - duilio.me](http://duilio.me/)


			[Laravel Recipes](http://laravel-recipes.com/)


			[Laravel and PHP Video Tutorials](https://laracasts.com/lessons)


			[Laravel | Fernando Gaitán](http://fernando-gaitan.com.ar/category/laravel/)


			[Laravel From Scratch](https://laracasts.com/series/laravel-from-scratch)


			[Laravel en Español - Comunidad Hispanoamericana de Laravel](http://laraveles.com/foro/)


			[laravel-4-uber-quick-start-with-auth-guide](http://fideloper.com/laravel-4-uber-quick-start-with-auth-guide?utm_source=nettuts&utm_medium=article&utm_content=api&utm_campaign=guest_author)


			[jasonlewis.me](http://jasonlewis.me/)


			[The Modern PHP Developer | Tuts+ Premium](https://tutsplus.com/2013/03/the-modern-php-developer/)


			[marcelgsantos/learning-oop-in-php](https://github.com/marcelgsantos/learning-oop-in-php)


			[Keyvan Akbary](http://keyvanakbary.com/)


		**Strings** [https://typeable.io/blog/2021-08-17-unicode.html](https://typeable.io/blog/2021-08-17-unicode.html)


		**ORMs** [https://seldo.com/posts/orm_is_an_antipattern](https://seldo.com/posts/orm_is_an_antipattern)


	[Infrastructure](13e6ebf0-d099-4e6f-9752-0d8edbe06fa7)


		[The Twelve-Factor App](http://12factor.net/)


		[Goodbye Microservices: From 100s of problem children to 1 superstar · Segment Blog](https://segment.com/blog/goodbye-microservices/)


		Interesting blog [danluu.com](http://danluu.com/)


		### Docker


		[Get started w/ Docker (full collection of useful learning materials) : docker](https://www.reddit.com/r/docker/comments/3jnxmb/get_started_w_docker_full_collection_of_useful/)


		[https://twitter.com/francescociull4/status/1344912796413259777?s=12](https://twitter.com/francescociull4/status/1344912796413259777?s=12)


		nginx


		Let’s Encrypt


		Caddy


	[Leadership](4a855c63-0eaa-4330-a179-55a49fb1f9af)


		[https://github.com/LappleApple/awesome-leading-and-managing](https://github.com/LappleApple/awesome-leading-and-managing)


		[Clearbit's approach to management](https://blog.clearbit.com/managers-handbook-tldr/amp/?__twitter_impression=true)


		[meetup/engineering-roles: Meetup's Engineering Ladder](https://github.com/meetup/engineering-roles)


		[raylene/eng-handbook: A developer's guide to management: an open-sourced handbook for leading software engineering teams.](https://github.com/raylene/eng-handbook)


		**Open Sourced Comapany Matrix** [https://www.progression.fyi](https://www.progression.fyi/)


		[https://github.com/charlax/engineering-management](https://github.com/charlax/engineering-management)


		[https://www.figma.com/blog/figmas-engineering-values/](https://www.figma.com/blog/figmas-engineering-values/)


		[https://www.okayhq.com/blog/engineering-productivity-can-be-measured](https://www.okayhq.com/blog/engineering-productivity-can-be-measured)


		**My Heroku values** [https://gist.github.com/adamwiggins/5687294](https://gist.github.com/adamwiggins/5687294)


		## Estimations


		“I’ll Finish It This Week” And Other Lies [https://arxiv.org/pdf/2103.16574.pdf](https://arxiv.org/pdf/2103.16574.pdf)


		Estimations [https://www.deconstructconf.com/2019/john-feminella-not-even-wrong](https://www.deconstructconf.com/2019/john-feminella-not-even-wrong)


		**Estimations** [https://www.youtube.com/watch?v=QVBlnCTu9Ms](https://www.youtube.com/watch?v=QVBlnCTu9Ms&ab_channel=AllenHolub)


		## Trust


		[Tom Dale en Twitter: "As a senior engineer in a new role, it's tempting to focus on bold, sweeping changes that justify your lofty title. This is a mistake. Your first order of business is building trust with your team. Nothing erodes that trust like revisiting plans they're already executing on."](https://twitter.com/tomdale/status/1189615599086903302)


		[https://m.signalvnoise.com/the-3-most-effective-ways-to-build-trust-as-a-leader](https://m.signalvnoise.com/the-3-most-effective-ways-to-build-trust-as-a-leader/)


		[https://www.kitchensoap.com/2012/10/25/on-being-a-senior-engineer](https://www.kitchensoap.com/2012/10/25/on-being-a-senior-engineer/)


		**Carrer path** [https://github.com/92bondstreet/awesome-engineering-path](https://github.com/92bondstreet/awesome-engineering-path)


		[Lessons from 6 software rewrite stories - Herb Caudill](https://medium.com/@herbcaudill/lessons-from-6-software-rewrite-stories-635e4c8f7c22)


		**Good judgement** [https://twitter.com/dan_abramov/status/1463718359262973953](https://twitter.com/dan_abramov/status/1463718359262973953)


		**PM Quick wins** https://mobile.twitter.com/jackiebo/status/1468368840039882753?s=20


		[Code review](cd31cd02-210d-45e5-a64e-d3b751b40301)


			[link_preview](https://github.com/bloodyowl/review-guidelines)


			Code Review: [https://mtlynch.io/tags/code-review](https://mtlynch.io/tags/code-review/)


		[Interviews](bcbd82c9-4c16-4de7-89d0-8bf1694a642f)


			Interesting questions [https://twitter.com/joulee/status/1392504865352417284](https://twitter.com/joulee/status/1392504865352417284)


			The MEGA interview guide [danieldelcore/mega-interview-guide: The MEGA interview guide](https://github.com/danieldelcore/mega-interview-guide)


			Reverse interview: [https://github.com/viraptor/reverse-interview](https://github.com/viraptor/reverse-interview)


		[Other must skills](b815eea3-06a0-4e2e-8cc4-c3f08ac3f885)

			1. How to run a meeting, and no, being the person who talks the most in the meeting is not the same thing as running it
			2. How to write a design doc, take feedback, and drive it to resolution, in a reasonable period of time
			3. How to mentor an early-career teammate, a mid-career engineer, a new manager who needs technical advice
			4. How to indulge a senior manager who wants to talk about technical stuff that they don’t really understand, without rolling your eyes or making them feel stupid
			5. How to explain a technical concept behind closed doors to a senior person too embarrassed to openly admit that they don’t understand it
			6. How to influence another team to use your solution instead of writing their own
			7. How to get another engineer to do something for you by asking for help in a way that makes them feel appreciated
			8. How to lead a project even though you don’t manage any of the people working on the project
			9. How to get other engineers to listen to your ideas without making them feel threatened
			10. How to listen to other engineers’ ideas without feeling threatened
			11. How to give up your baby, that project that you built into something great, so you can do something else
			12. How to teach another engineer to care about that thing you really care about (operations, correctness, testing, code quality, performance, simplicity, etc)
			13. How to communicate project status to stakeholders
			14. How to convince management that they need to invest in a non-trivial technical project
			15. How to build software while delivering incremental value in the process
			16. How to craft a project proposal, socialize it, and get buy-in to execute it
			17. How to repeat yourself enough that people start to listen
			18. How to pick your battles
			19. How to help someone get promoted
			20. How to get information about what’s really happening (how to gossip, how to network)
			21. How to find interesting work on your own, instead of waiting for someone to bring it to you
			22. How to tell someone they’re wrong without making them feel ashamed
			23. How to take negative feedback gracefully

		[1 to 1's](46acd68a-1417-4819-add2-ac012b474822)


			## **About Manager**

			- Are there any obstacles I can remove for you?
			- As your manager, what would you like me to stop, start, or continue doing?
			- At what point in the past week were you most frustrated with or discouraged by your work? What can I do to help you manage that?
			- Do you feel you’re getting enough feedback? Why/why not?
			- Do you have any feedback for me?
			- Do you think that you receive enough feedback? Is feedback helpful for your personal development? What can I do to help you get the feedback you want?
			- How can I better support you?
			- How can I make your days more fulfilling?
			- How could I do a better job communicating with you?
			- How do you prefer to receive feedback?
			- How might I make this project more challenging or interesting for you?
			- I'd like to improve as a manager and I could really use your help. Next week, would you be willing to share some feedback on one to two things you think I could do better as your manager?
			- If you were me, what changes would you make?
			- I’m trying to make my 1-on-1s better and would appreciate your honest feedback on this one — what did you like about it, and what could be improved?
			- I’ve noticed that our last several 1-on-1s have stayed pretty surface. What are your honest impressions of this meeting? What could we be doing differently or better?
			- What additional resources can I provide for you between now and the next time we meet?
			- What are your impressions of our 1-on-1s? What could we do differently or better?
			- What are your thoughts on my changes?
			- What aspect of your job you would like more help or coaching?
			- What aspects of your work would you like more or less direction from me?
			- What can I be doing better to help you in your job?
			- What can I do as a manager to make your work easier?
			- What can I do better or differently as your manager to support you?
			- What can I do for you that I'm not?
			- What can I do to help remove obstacles?
			- What can I do to help you achieve you current goals and priorities?
			- What can I do to help you enjoy your work more or remove roadblocks to progress?
			- What can I do to help you?
			- What can I do to make things more manageable?
			- What can I do to make your job easier?
			- What could I do as a manager to make your work easier?
			- What do you like about my management style? What do you dislike?
			- What do you think I should know about the project, but might not?
			- What have your past managers done that you’d like me to also do or not do?
			- What is something I could do better? What feedback do you have for me?
			- What is something I could have done better? What are the situations that I could have helped more but didn’t?
			- What is the biggest challenge you are currently facing? How can I help with that?
			- What is the one thing that you need the most from me?
			- What is the percentage of my involvement in your daily tasks? Would you prefer more or less?
			- What would you like to know about me?
			- What would you like to see change about these discussions? How could we make them more useful for you?
			- What’s your favorite thing I do as a manager of this team I should keep doing?
			- Where do you think I can be most helpful?
			- Which areas would you like more or less direction from me on your work?
			- Would you like more coaching? What aspect of your job do you like more help and coaching on?

			## **Career development**

			- Are there any events or training you’d like to attend to help you grow your skills?
			- Are there any projects you’d really like to work on if you were given the opportunity?
			- Could you see yourself making progress on more of your goals here? What would need to change to do so?
			- Do you feel like you are learning at work? What are the new things you learned lately? What are the areas you want to learn about?
			- Do you feel like you’re making progress on your big goals here? Why or why not?
			- Do you feel we’re helping you advance your career at a pace you would like?
			- Do you have the tools you need to reach your goals?
			- During this meeting you’ve mentioned that you’d like to pursue X. What steps can you take toward that before our next 1-on-1?
			- Have you ever felt undervalued here?
			- Have you given any more thought to your long-term goals since our last meeting? What are your latest thoughts?
			- How do you feel you are progressing in your career?
			- How do you think about your progress on your big goals? What needs to be done to move towards the goals? What can we do to help?
			- How do you think you did on your performance review this year? What do you think the results will be?
			- How is your current work helping or hurting your professional development?
			- If you were to create your ideal position, how would it differ from what you are currently doing?
			- Imagine it’s two years from now, and things have gone well: What has been your role in that? What does your role look like?
			- Is there a different way we can develop your skills outside of traditional training?
			- Is there an aspect of your job you would like more help or coaching?
			- Tell me about something new you learned since we met last.
			- To help identify and clarify the goal: What do you want to achieve? What will you do to achieve it? When will you do it? Who do you need to involve? When should you see results?
			- What about this goal is important to you and what will be different when you achieve the goal?
			- What actions will you take before our next 1-on-1 to make progress on X? (Also discuss and agree on actions you will take to help.)
			- What additional training or education would you like?
			- What are some of the work projects you’re most proud of, and what do you think you might want to do next?
			- What are the projects you would be interested in working on next?
			- What are two to three new skills you’d like to learn on the job? What about those skills interests you?
			- What are your big dreams in life? Are you making progress on them?
			- What are your goals (for our group for you personally)
			- What are your long term goals? Have you thought about them?
			- What are your super powers? What powers would you like to develop?
			- What areas of your job do you find difficult that getting better skills at would help?
			- What big questions do you have about your career opportunities in the future?
			- What can I do to take action or make progress on what we talked about today?
			- What can you do to take action or make progress on what we talked about today?
			- What capabilities do you want to develop?
			- What development areas do you want to work on in the coming weeks?
			- What do you see as the next step in your career?
			- What do you want to be doing in 5 years? 10 years? 3 years?
			- What do you want to do in your next job?
			- What else can I be doing to help you grow/advance in your career?
			- What goals have you set for your career?
			- What kind of training or experience would be most helpful to you right now?
			- What opportunities have you had recently to learn something new?
			- What other roles here could you see yourself in down the line? Or what areas would you like to explore?
			- What parts of your job would you like to deepen your skills in or get additional training in?
			- What professional goals would you like to accomplish in the next 6 to 12 months, and what makes you say that?
			- What skills are required to reach your goals?
			- What skills do you have that you think are underutilized?
			- What skills would you like to develop right now?
			- What sort of progress have you made on the next steps we discussed last time?
			- What work are you doing here that you feel is most in line with your long term goals?
			- What would make this your perfect job?
			- What would you like to learn about in the future?
			- What’s one thing we could do today to help you with your long term goals?
			- Where do you see your career in 1 year, 3 years? What can you do to make sure you reach those goals? How can we as HR help you to reach those goals (assuming the goals relate to the company)?
			- Where do you see your career in the next (2/5/10) years?
			- Where do you see yourself in three years? Five years?
			- Which career or development goals do you feel like you’re not able to focus on right now?
			- Which part of the work here do you feel as most relevant to your long-term goals? What kinds of projects do you want to take part in to move toward your goals?
			- Who in the company would you like to learn from? What do you want to learn?

			## **Conversation starters**

			- Are you on track to meet the deadline?
			- Hey, what’s going on?
			- How are you? How is life outside of work?
			- How are your parents/grandparents? Where do they live? Do you visit them?
			- How is your family?
			- How was your weekend?
			- How’s it going?
			- If around a holiday: Do you celebrate [Holiday]? If so, can I ask what are you plans?
			- If they have children: How is [name of child] doing? (Ask something related to their age like starting school, playing sports, or other interests.)
			- I’ve noticed you’re a little quieter than usual. Is there anything you’d like to talk about?
			- So, what’s on your mind? (or Anything on your mind?)
			- Tell me a story...
			- Tell me about anything you stumbled over.
			- Tell me about last week.
			- Tell me about what you’ve been working on.
			- Tell me about your family/weekend/ activities?
			- Tell me about your week – what’s it been like?
			- What can I do to make your day better?
			- What do you like to do in your free time? What are your hobbies?
			- What have you been doing for fun lately?
			- What would you like to focus on at this meeting?
			- What would you like to start with?
			- What's something I don't know, but should?
			- Who do you really admire? Why? (People often admire those they want to become)
			- Would you like to walk today, or go somewhere else outside the office?
			- Would you update me on Project X?

			## **Job satisfaction**

			- Are you happy here? What makes you say that?
			- Are you happy with your recent work? Why or why not?
			- Can you name three things we can do to help so you can enjoy your job more?What is the best accomplishment you had since you are here? Do you feel appreciated for it?
			- Do you feel challenged at work? Are you learning new things?
			- Do you feel like you're growing in your role? What makes you say that?
			- Do you feel over-worked, under-worked, or just the right workload?
			- Do you think our company is loyal to its employees? Why or why not?
			- Happiness level, 1 to 10?
			- How are you feeling about the project?
			- How are you feeling about your role?
			- How did that affect you?
			- How did that make you feel?
			- How do you feel your work/life balance is right now?
			- How do you think of your current workload and how are you coping with them?
			- How do you think that least favorite thing affects your overall performance?
			- How many hours a day do you feel you’re productive? How could we help you be more productive?
			- If you could change what happened, how would you alter it?
			- If you could work on anything for the next month, what would it be? What makes you say that?
			- In our last 1-on-1 you mentioned that you’d like to grow in X — how has that been going?
			- In our last 1-on-1 you mentioned you were frustrated by X and wanted to try Y as a solution. How has that been going?
			- In what ways does your current position allow you to use your skills and talents?
			- I’ve noticed X about the project… Can you help me understand that better? Talk me through your process.
			- Tell me about what you’ve learned on this project.
			- What are you most excited about?
			- What are you most worried about?
			- What are your biggest concerns about your current project(s)?
			- What aspect of this project has been particularly interesting for you?
			- What could I do to make you enjoy your work more?
			- What did you like most/least about that?
			- What do you enjoy the most in your current role?
			- What do you feel is your greatest accomplishment here?
			- What do you feel like you're learning from this project?
			- What do you like most about working on our team?
			- What do you like most about your job today?
			- What do you like the least?
			- What do you need or want to accomplish and by when?
			- What do you think caused that to happen?
			- What do you think has gone well? What do you think you could have done better? What, if anything, would you like to do, but haven't been able to?
			- What do you think you could be doing differently?
			- What drives you? What motivates you to come to work each day?
			- What feedback/praises have you been getting about your current priorities?
			- What frustrates you about the project?
			- What have you tried so far to make progress on it?
			- What interests you about the project(s) you’re currently working on, and why?
			- What is your favorite/least favorite thing about your work right now?
			- What talents do you have that you feel we are fully utilizing? Which of your talents are we not fully leveraging?
			- What was that experience like for you?
			- What would be the most helpful thing for you to take away from this conversation in order to make progress on it?
			- What would convince you to leave for a job somewhere else?
			- What would make you leave this job for another?
			- What’s a recent situation you wish you handled differently? What would you change?
			- What’s an area of your work you want to improve?
			- What’s one thing about your job that, if we fixed, would make you never want to leave?
			- What’s one thing that could make your work more satisfying, and why?
			- What’s the best part of your job?
			- What’s the worst part about your job?
			- What’s working well for you in your current position?
			- What’s your No. 1 problem right now? How are you feeling about it?
			- When was the time you enjoyed working here the most?
			- Which areas make you feel like your hands are tied or you are unable to reach your full potential?
			- Which areas would you like to spend more time on and why?
			- Which parts of your project are unclear or confusing?

			## **Other**

			- As a kid, what did you want to be when you grew up?
			- How are things going for you outside of work?
			- If you had millions of dollars, what would you do every day?
			- What did you do for fun in the past that you haven’t had as much time for lately?
			- What haven’t you tried yet?
			- What ideas can you bring in from past successes?
			- What questions do you have about the project?
			- What would you be doing right now if we weren’t having this meeting? How do you feel about being taken away from that task?
			- What’s one thing we could change about work for you that would improve your personal life?

			## **Team and company**

			- Are there any aspects of our culture you wish you could change?
			- Are there any meetings or discussions you feel you should be a part of that you’re not? Are you included in any you don’t want to be a part of?
			- Are there any problems or issues that I should know about?
			- Are there any roles in the company you’d like to learn more about?
			- Are you uncomfortable giving any of your peers constructive criticism? If so, why?
			- Can you share some of the details around that particular issue? (Who was involved? Where? When? For how long?)
			- Could you tell me a little more about that?
			- Do you feel adequately supported by other team members? What makes you say that?
			- Do you feel like you’re on the same page with the team? How often do you think you need meetings to ensure you stay that way?
			- Do you have a clear understanding of the new goals and expectations? What makes you say that?
			- Do you help other members on the team? Do others help you when you need it?
			- Has anyone on the team ever made you feel uncomfortable? What happened?
			- How are you feeling about the company’s future overall? What makes you say that?
			- How are you feeling about the recent news? Why do you say that?
			- How could we be more creative or innovative as a company?
			- How could we change our team meetings to be more effective?
			- How is the new situation/development affecting your work? What could be getting in the way of your being effective?
			- How well do you feel like you relate to you coworkers? Do you view them as friends, acquaintances, or strangers?
			- How would you describe the division of work among team members?
			- How would you describe the personality of the team? What sort of person would be a good fit here? What sort of person would add something we're currently missing?
			- How would you rate our communication as a team?
			- How would you say we're doing at working together as team? What makes you say that?
			- If we could improve in any way, how would we do it?
			- If you were CEO, what’s the first thing you’d change?
			- Is any part of your project unclear or confusing?
			- Is everyone pulling their weight on the team?
			- Is there a situation you’d like my help with?
			- Is there anybody in the team that you find it difficult to work with? Can you tell me why?
			- Is there anything blocking you from getting your work done?
			- Is there anything that’s slowing you down from getting your work done?
			- Is there anything you’d like to see change about the team, and if so, why?
			- Is your job what you expected when you accepted it?
			- What additional resources from me would be helpful for you as you solve this problem?
			- What are some possible ways to get the solution you need?
			- What are some ways we could improve at teamwork? What makes you say that?
			- What are we doing that you think we should stop doing, and why?
			- What are we not doing that we should be doing? What makes you say that?
			- What are your favorite parts about our culture?
			- What are your next steps to make progress on this problem?
			- What are your top three motivators?
			- What area of the company would you like to learn more about?
			- What areas are ahead of schedule?
			- What characteristics make someone a good fit for our team? How would you look for those characteristics in an interview?
			- What concerns do you have about the change that haven't been addressed?
			- What could you have done differently?
			- What do you do when you get stuck on something? What is your process of getting unstuck? Who is the team member you turn to for help?
			- What do you like about working here? What’s not fun about working here?
			- What do you think about the amount of feedback in our team? When do others give feedback to you? Would you like to hear more feedback from other team member and me?
			- What do you think about _________?
			- What do you think are the key skills for your role? How would you rate yourself for each of them?
			- What do you think would help us work together better?
			- What do you think you can do to fix that problem?
			- What excites you about our business? The company? What concerns you?
			- What is the #1 Problem at our company? Why?
			- What is the company not doing today that we should do to better compete in the market?
			- What kind of communication or information do you wish you had more of?
			- What part of your job do you wish you didn’t have to do?
			- What sort of resources could you use right now to make things more manageable?
			- What would you like to learn more about this year?
			- What would you like to see change here? Why do you say that?
			- What’s an inexpensive thing we could do to improve our office environment for the team?
			- What’s going well and not so well with the new situation/development? Why do you think this might be happening?
			- What’s one thing we should change about how our team works together?
			- What’s one thing we’d be _crazy_ not to do in the next quarter to improve our product?
			- What’s something you feel is undervalued that you contribute to the team?
			- What’s the biggest opportunity we’re missing out on?
			- What’s the biggest thing you’d like to change about our team?
			- What’s the No. 1 problem with our organization, and what do you think's causing it?
			- What’s the No. 1 problem with our organization? Why?
			- What’s the number one problem within our organization? Why?
			- Where do you think we can do better?
			- Which areas would you would like more feedback on?
			- Which company values do you like the most? Which the least? Why?
			- Who are you friends with at work? (Shown to be a key to enjoying your job)
			- Who do you admire within the company and why?
			- Who has really been kicking ass lately?
			- Who inspire you in the team? Whose opinions do you respect? What have they done?
			- Who is kicking ass on the team? What have they done?
			- Who is really kicking ass in the company? Who do you admire?
			- Who on the team do you have the most difficulty working with? Why?
			- Who would you like to work more often with? Why?
			- Whom in the team do you want to learn from? Whom do you get valuable feedback from?
			- Why do you think [employee who recently quit] left? What did they tell you?

			## **Work-life**

			- How are you feeling about work?
			- How are you going to approach this?
			- How are you planning to balance work and personal life this year?
			- How can I help…? (be more productive/happier at work/enjoy work more/etc)
			- How do you feel about your work/life balance?
			- How is your workload right now?
			- If you could change one thing about your job today, what would you change?
			- Is there anything that you need from me?
			- Is there anything that you’re struggling with?
			- Is there anything you’d like to be doing on your own time to relieve stress that you’re not getting to? How can I help you achieve those personal goals?
			- What about work is frustrating?
			- What about your job is most satisfying for you?
			- What are 3 things could we do to improve your productivity if money was no object?
			- What are the biggest time wasters for you each week?
			- What are the most important things you will focus on before we meet next?
			- What are you doing for yourself outside of work?
			- What are your most significant accomplishments since we last met?
			- What areas of your work are you confident about?
			- What could we change about work that would improve the rest of your life?
			- What do you do when you feel low energy or unmotivated?
			- What does your ideal weekday look like?
			- What is an ideal, productive day at work for you? Walk me through the day…
			- What is the most important thing we need to discuss today?
			- What makes you excited and motivated to work on a project?
			- What obstacles are you encountering right now?
			- What part of the day do you have the most energy and focus? When do you have the least? What changes could we make to your work schedule to accommodate this?
			- What part of your work routine do you find is working best? What area do you want to improve?
			- What questions do you have about this project?
			- What stands in your way?
			- What suggestions do you have?
			- What was difficult this week? what have you learned?
			- What were your biggest time wasters or roadblocks last week or the week before?
			- What worries you?
			- What worries you? What’s on your mind?
			- What, if anything, did you used to do that you find you don’t have time for right now?
			- What’s an inexpensive thing we could do to improve our office environment?
			- When is your next vacation?
			- When was your last vacation?
			- When you get stuck on something, what is your process for getting unstuck? Who do you turn to for help?
			- Which part of the day do you feel most productive? When do you feel that your energy and focus are at the lowest level? What are the changes that can be made so you can take the best out of a work day?

		[Questions](3126cf82-bc03-447c-8fd6-16e84e5c0499)

			- [https://joshkaufman.net/how-to-ask-useful-questions](https://joshkaufman.net/how-to-ask-useful-questions/)
			- [https://josh.works/better-questions](https://josh.works/better-questions)
			- [https://dev.to/sloan/how-to-ask-senior-devs-for-help-17ji](https://dev.to/sloan/how-to-ask-senior-devs-for-help-17ji)
			- [http://www.catb.org/esr/faqs/smart-questions.html](http://www.catb.org/esr/faqs/smart-questions.html)
			- [https://twitter.com/cassiecodes/status/1303770566793592834](https://twitter.com/cassiecodes/status/1303770566793592834)
			- [https://twitter.com/bscholl/status/1296986031380545537](https://twitter.com/bscholl/status/1296986031380545537)
			- [https://twitter.com/GergelyOrosz/status/1236606480763232257](https://twitter.com/GergelyOrosz/status/1236606480763232257)

		[Being a CEO](e57b0bd5-dd6c-4be0-b7e4-5927cfd84105)


			There are two loops of being a great CEO. The faster these loops run, the better:


			1) 
			  a) Hire the best people.
			  b) Reinforce the vision.
			  c) Don't run out of money.
			2) 
			  a) Do people know what they should be doing? 
			  b) Do they know why? 
			  c) Are they doing it?


		[Engineering Director job](6ddec9c2-a48d-40d4-9feb-d01556f4a602)


			[https://twitter.com/__apf__/status/1363861400334921732?s=12](https://twitter.com/__apf__/status/1363861400334921732?s=12)


			Folks often ask me what I do at work. What even IS an engineering director? I don’t write code all day anymore, so it seems very mysterious. Here’s my answer: **people, processes, priorities**.


			### People


			Hiring, career growth, happiness, performance management, compensation, team culture, psychological safety, coaching the managers in my org. This is perhaps the most visible and obvious aspect of management.


			### Processes


			Are we making good decisions in a timely manner? Are we looking at the right metrics for launches? Are we planning and executing well? Is the product team far enough ahead of engineering? Are our technical decisions taking the right factors into account?


			### Priorities


			Are we working on the right things? Are we sufficiently focused? Have we diversified our bets? Are we investing appropriately in maintenance, testing, and technical debt?


	[Security](8834b5f7-ed32-48bb-898b-a7e4966ea7b2)


		[https://iplocate.xyz](https://iplocate.xyz/)


		Check different encodings [https://gchq.github.io/CyberChef](https://gchq.github.io/CyberChef/)


		[https://github.com/Lissy93/personal-security-checklist](https://github.com/Lissy93/personal-security-checklist)


	[Quality](483865b2-5f7f-4c75-9079-c3455eba742c)


		[Testing](2dd78aa9-5b85-4417-afea-449af5b3a95c)


			[https://github.com/goldbergyoni/javascript-testing-best-practices](https://github.com/goldbergyoni/javascript-testing-best-practices)


		[https://github.com/ligurio/awesome-software-quality](https://github.com/ligurio/awesome-software-quality)


		![](https://www.morling.dev/images/code_review_pyramid.png)


	[Recommended talks](34e3e2f3-8732-41df-8c75-2dd328c0ba56)


		**Simplicity Matters by Rich Hickey @ Rails Conf 2012** 
		[https://www.youtube.com/watch?v=rI8tNMsozo0](https://www.youtube.com/watch?v=rI8tNMsozo0)


		**Lambda Calculus - Fundamentals of Lambda Calculus & FP in JavaScript**
		[https://www.youtube.com/watch?v=3VQ382QG-y4](https://www.youtube.com/watch?v=3VQ382QG-y4)


		[https://www.youtube.com/watch?v=pAnLQ9jwN-E](https://www.youtube.com/watch?v=pAnLQ9jwN-E&t=885s)


		**Evan Czaplicki - Let's be mainstream! User focused design in Elm** [https://www.youtube.com/watch?time_continue=11&v=oYk8CKH7OhE](https://www.youtube.com/watch?time_continue=11&v=oYk8CKH7OhE)


		**Cheng Lou - On the Spectrum of Abstraction at react-europe 2016** [https://www.youtube.com/watch?v=mVVNJKv9esE](https://www.youtube.com/watch?v=mVVNJKv9esE)


		**Oh Composable World! by Brian Lonsdorf**


		[https://www.youtube.com/watch?v=SfWR3dKnFIo](https://www.youtube.com/watch?v=SfWR3dKnFIo)


		**Hey Underscore, You're Doing It Wrong! by Brian Lonsdorf**


		[https://www.youtube.com/watch?v=m3svKOdZijA](https://www.youtube.com/watch?v=m3svKOdZijA)


		**All the Little Things by Sandi Metz @ RailsConf 2014** 


		[https://www.youtube.com/watch?v=8bZh5LMaSmE](https://www.youtube.com/watch?v=8bZh5LMaSmE)


		**The Future of Programming by Bret Victor**


		[https://www.youtube.com/watch?v=8pTEmbeENF4](https://www.youtube.com/watch?v=8pTEmbeENF4)


		**Architectural Thinking - Mark Richards**


		[https://www.youtube.com/watch?v=5YilcPUlbaI](https://www.youtube.com/watch?v=5YilcPUlbaI)


		**André Staltz - How to Think - Uphill Conf 2019**


		[https://www.youtube.com/watch?v=_fB8GRotdrc](https://www.youtube.com/watch?v=_fB8GRotdrc)


		**Tangible Functional Programming**
		[https://www.youtube.com/watch?v=faJ8N0giqzw&ab_channel=GoogleTechTalks](https://www.youtube.com/watch?v=faJ8N0giqzw&ab_channel=GoogleTechTalks)


		**Fun, Funky, Functional: The Pursuit of Better User Interfaces for Programming**
		[https://www.youtube.com/watch?v=1gGd7pKSpRM&ab_channel=ACMSIGPLAN](https://www.youtube.com/watch?v=1gGd7pKSpRM&ab_channel=ACMSIGPLAN)


	[Learning Platforms](fc0b080f-9c8e-482b-bc21-4f5dfae5a085)


		[Courses](bcabb310-f67e-4e52-9ad0-2e6ed0da4be9)


		[The book of secret knowledge: A collection of inspiring lists, manuals, cheatsheets, blogs, hacks, one-liners, cli/web tools and more.](https://github.com/trimstray/the-book-of-secret-knowledge)


		[sindresorhus/awesome: Awesome lists about all kinds of interesting topics](https://github.com/sindresorhus/awesome)


		[EbookFoundation/free-programming-books](https://github.com/EbookFoundation/free-programming-books/blob/master/free-programming-books-es.md)


		Free resources for developers [free-for.dev](https://free-for.dev/#/)


		[Design Patterns & Refactoring](https://sourcemaking.com/)


		[Refactoring and Design Patterns](https://refactoring.guru/)


		[OverAPI.com | Collecting all the cheat sheets](http://overapi.com/)


		[DevDocs](http://devdocs.io/)


		[ZEEF | Curated Directory | Find information through people](https://zeef.com/)


		[Welcome to CodePicnic. Your code to go](https://codepicnic.com/)


		[Bento - Learn how to code](http://www.bentobox.io/)


		[MIT OpenCourseWare: Spanish | MIT OpenCourseWare | Free Online Course Materials](http://ocw.mit.edu/courses/translated-courses/spanish/)


		[LibrosWeb](http://www.librosweb.es/)


		[Miriada X](https://www.miriadax.net/)


		[Khan Academy](https://es.khanacademy.org/)


		[edX - online courses and classes from the world's best](https://www.edx.org/)


		[codehero.co](http://codehero.co/)


		[Ingeniería de arranque - Universidad de Stanford | Coursera](https://www.coursera.org/course/startup)


		[uno de piera - Tutoriales sobre desarrollo web y móvil, angularjs, nodejs, codeigniter, phalcon, laravel, php, jQuery, mysql](http://uno-de-piera.com/)


		[OpenWebinars.net - Cursos Online de Programación y Sistemas](https://openwebinars.net/)


		[Learnable](https://learnable.com/)


		[DevCode.la | Aprender a programar fácilmente](http://www.devcode.la/)


		[Cursos online gratuitos - Genbeta](http://www.genbeta.com/tag/cursos-online-gratuitos)


		[OpenLibra: la Biblioteca Libre Online. | EtnasSoft](http://www.etnassoft.com/biblioteca)


		[Web technology for developers | MDN](https://developer.mozilla.org/en-US/docs/Web)


		[Best Online Courses | Udemy](https://www.udemy.com/courses/)


		[Ejercicios y katas de programación | Solveet!](http://www.solveet.com/)


		[CodeCombat - Learn how to code by playing a game](http://codecombat.com/play)


		[UNED](https://unedcoma.es/)


		[JavaScript - Code School](https://www.codeschool.com/paths/javascript)


		[Online video tutorials & training | lynda.com](http://www.lynda.com/default.aspx)


		[Offerings](https://university.mongodb.com/courses)


		[Code4Startup - Learn Ruby on Rails, AngularJS, NodeJS, Bootstrap, HTML5, CSS3 by cloning Real-life Startups](https://code4startup.com/)


		[Atlas Beta - The new learning environment from O’Reilly](http://chimera.labs.oreilly.com/)


		[Your Web, documented · WebPlatform.org](http://www.webplatform.org/)


		[Adobe KnowHow](https://www.adobeknowhow.com/)


		[23 Webs para descargar libros gratis y sin conflictos sobre los derechos de autor](http://www.genbeta.com/multimedia/23-webs-para-descargar-libros-gratis-y-sin-conflictos-sobre-los-derechos-de-autor)


		[free-programming-books/free-programming-books-es.md at master · vhf/free-programming-books · GitHub](https://github.com/vhf/free-programming-books/blob/master/free-programming-books-es.md)


		[reSRC · List of Free Programming Books](http://resrc.io/list/10/list-of-free-programming-books/)


		[Coursera](https://www.coursera.org/course/startup)


	---


	[P = NP Problem](a7a0673c-8829-498e-84f0-1e19d897ad62)


		[https://www.youtube.com/watch?v=YX40hbAHx3s&ab_channel=hackerdashery](https://www.youtube.com/watch?v=YX40hbAHx3s&ab_channel=hackerdashery)


		[https://twitter.com/AlejandroPiad/status/1451111039207096323](https://twitter.com/AlejandroPiad/status/1451111039207096323)


[Design](418ad993-b9fd-491b-a1eb-f26c6dcdd1e0)


	[https://github.com/gztchan/awesome-design](https://github.com/gztchan/awesome-design)


	[Carefully Crafted UI Design Assets](https://ui8.net/)


	[Tools](966bd563-b53f-4595-b654-cc153c9a1eda)


		[https://github.com/sw-yx/spark-joy](https://github.com/sw-yx/spark-joy)


		[GoyaPixel](http://jackschaedler.github.io/goya/)


		[PlaceIt by Breezi - Generate Product Screenshots in Realistic Environments](http://placeit.breezi.com/)


		[IcoMoon - Custom Built Icon Fonts](http://icomoon.io/)


		[Patternizer - Stripe Pattern Generator Tool](http://patternizer.com/qzi9)


		[Favicon Generator for all platforms: iOS, Android, PC/Mac...](http://realfavicongenerator.net/)


		[sprites](http://www.spritecow.com/) - Generate PNG sprites


		[Instant Logo Search](http://instantlogosearch.com/)


		[https://www.thegoodlineheight.com](https://www.thegoodlineheight.com/) - Line height


		Tool directory: [https://nodesign.dev/](https://nodesign.dev/)


	[Stock](ec7bdad9-fc92-4f65-9f86-60ac7387503f)


		[https://github.com/neutraltone/awesome-stock-resources](https://github.com/neutraltone/awesome-stock-resources)


		[Icojam – high quality icons](http://www.icojam.com/)


		[Subtle Patterns | Free textures for your next web project.](http://subtlepatterns.com/)


		[Stockvault - Free Stock Photos - Free Images](http://www.stockvault.net/)


		[Original Mockups - Designing Mockups People Love](http://originalmockups.com/)


		[heyalexej/awesome-images](https://github.com/heyalexej/awesome-images)


	[Product Design](127510e2-29d5-43ed-93ba-7536f59ac4bf)


		[Refactoring UI](78375bdb-89c3-4148-a5ef-92e381f29ae8)


			[image](https://s3.us-west-2.amazonaws.com/secure.notion-static.com/22473ba3-823e-4d38-b816-c23ac5c8c709/Icons_v1.0.2.zip?X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Content-Sha256=UNSIGNED-PAYLOAD&X-Amz-Credential=AKIAT73L2G45EIPT3X45%2F20220725%2Fus-west-2%2Fs3%2Faws4_request&X-Amz-Date=20220725T091418Z&X-Amz-Expires=3600&X-Amz-Signature=0a7b675054e686f87da7b3a589901815fa6ed751e7f686d7246f356b81fafac2&X-Amz-SignedHeaders=host&x-id=GetObject)


			[image](https://s3.us-west-2.amazonaws.com/secure.notion-static.com/cebd8125-16e9-4764-97ef-c9d63410e2a6/Component_Gallery_v1.1.0.sketch?X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Content-Sha256=UNSIGNED-PAYLOAD&X-Amz-Credential=AKIAT73L2G45EIPT3X45%2F20220725%2Fus-west-2%2Fs3%2Faws4_request&X-Amz-Date=20220725T091418Z&X-Amz-Expires=3600&X-Amz-Signature=e580c9a6a104a92daf5d9c95c637bb2c1b973af4cb4e969d7e42f922f0be23c8&X-Amz-SignedHeaders=host&x-id=GetObject)


			[image](https://s3.us-west-2.amazonaws.com/secure.notion-static.com/f548461f-7544-4933-a544-28c2f69d277b/Component_Gallery_v1.1.0.pdf?X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Content-Sha256=UNSIGNED-PAYLOAD&X-Amz-Credential=AKIAT73L2G45EIPT3X45%2F20220725%2Fus-west-2%2Fs3%2Faws4_request&X-Amz-Date=20220725T091418Z&X-Amz-Expires=3600&X-Amz-Signature=dc2c92cf29aaadbf823440588aa3129aa60c2b387e5680a9c3fd39d196e1b97e&X-Amz-SignedHeaders=host&x-id=GetObject)


			[image](https://s3.us-west-2.amazonaws.com/secure.notion-static.com/7d28c66c-282c-475f-8f77-03bbe833bbcc/Color_Palettes_v1.1.0.sketch?X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Content-Sha256=UNSIGNED-PAYLOAD&X-Amz-Credential=AKIAT73L2G45EIPT3X45%2F20220725%2Fus-west-2%2Fs3%2Faws4_request&X-Amz-Date=20220725T091418Z&X-Amz-Expires=3600&X-Amz-Signature=e41f19fcbf795a70a3ecc17882301b258b24c3fad9ab5c39124d341b31b46dde&X-Amz-SignedHeaders=host&x-id=GetObject)


			[image](https://s3.us-west-2.amazonaws.com/secure.notion-static.com/e26aa579-4d62-43ee-8663-68d1f529ba3b/Color_Palettes_v1.1.0.pdf?X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Content-Sha256=UNSIGNED-PAYLOAD&X-Amz-Credential=AKIAT73L2G45EIPT3X45%2F20220725%2Fus-west-2%2Fs3%2Faws4_request&X-Amz-Date=20220725T091418Z&X-Amz-Expires=3600&X-Amz-Signature=1b12b8ef0a8306d716b2ace479734fe26dae97ccc1c22e9b9fd9d45c27a64be0&X-Amz-SignedHeaders=host&x-id=GetObject)


			[image](https://s3.us-west-2.amazonaws.com/secure.notion-static.com/a9cb3e0b-e445-4cef-84d1-53362b95c5e7/Color_Palettes_JSON_v1.1.0.zip?X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Content-Sha256=UNSIGNED-PAYLOAD&X-Amz-Credential=AKIAT73L2G45EIPT3X45%2F20220725%2Fus-west-2%2Fs3%2Faws4_request&X-Amz-Date=20220725T091418Z&X-Amz-Expires=3600&X-Amz-Signature=a88c454ff1b120230c23383ee0ab30a89eea198bb626b90edbb28f4800cd37f2&X-Amz-SignedHeaders=host&x-id=GetObject)


			[image](https://s3.us-west-2.amazonaws.com/secure.notion-static.com/fd5b5d59-26bb-4403-942d-5785d402224d/Refactoring_UI_v1.0.2.pdf?X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Content-Sha256=UNSIGNED-PAYLOAD&X-Amz-Credential=AKIAT73L2G45EIPT3X45%2F20220725%2Fus-west-2%2Fs3%2Faws4_request&X-Amz-Date=20220725T091418Z&X-Amz-Expires=3600&X-Amz-Signature=203174350b5ee8030518efb38819815f0f81853f5a16cf4b4d938f398a0968c0&X-Amz-SignedHeaders=host&x-id=GetObject)


			[image](https://s3.us-west-2.amazonaws.com/secure.notion-static.com/0e80cfed-0f46-412c-b4b7-d4e0121c67cd/Font_Recommendations_v1.0.1.pdf?X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Content-Sha256=UNSIGNED-PAYLOAD&X-Amz-Credential=AKIAT73L2G45EIPT3X45%2F20220725%2Fus-west-2%2Fs3%2Faws4_request&X-Amz-Date=20220725T091418Z&X-Amz-Expires=3600&X-Amz-Signature=459b58107856b5c7b6d2ff6995db36794f7983d0780f47fb44ab1fac6c6a664d&X-Amz-SignedHeaders=host&x-id=GetObject)


		[https://storybook.js.org](https://storybook.js.org/)


		[https://github.com/adobe/react-spectrum](https://github.com/adobe/react-spectrum)


		[https://github.com/react-figma/react-figma](https://github.com/react-figma/react-figma)


		[http://airbnb.io/react-sketchapp](http://airbnb.io/react-sketchapp/)


	[Icons](48747f10-4cfa-44dd-b04b-d1eb784fbf11)


		[https://github.com/astrit/css.gg](https://github.com/astrit/css.gg)


		[https://fontawesome.com](https://fontawesome.com/)


		[https://github.com/tabler/tabler-icons](https://github.com/tabler/tabler-icons)


	[Inspiration](cb8824af-3136-40fa-8181-556bf52f735b)


		## UI Examples


		[https://lookup.design/](https://lookup.design/)


		[https://design-encyclopedia.webflow.io/](https://design-encyclopedia.webflow.io/)


		[https://uidesigndaily.com/](https://uidesigndaily.com/)


		[https://www.uisources.com/](https://www.uisources.com/)


		[https://www.niceverynice.com/components](https://www.niceverynice.com/components)


		## UX Flows


		[https://www.saasframe.io](https://www.saasframe.io/)


		[Freebiesbug](http://freebiesbug.com/)


		[Designspiration — Design Inspiration](http://designspiration.net/)


		[Psddd - Beautiful Dribbble freebies for the creative professional](http://psddd.co/)


		[Media Queries](http://mediaqueri.es/)


		[Folio Focus - Gallery of Design Portfolios](http://foliofocus.com/)


		[Agencies](674a205e-72b4-4a60-a985-e1669c430a1a)


			[wearegoat](http://wearegoat.com/#!/works/)


			[https://josipkelava.com/](https://josipkelava.com/)


			[John Front » Portfolio of Ivan Tsankov,Freelance Graphic/Web Designer](http://www.johnfront.com/)


			[http://designerfirst.com/](http://designerfirst.com/)


	[Typography](eb067005-76a1-4d8f-94e2-1da3d579797b)


		[Specimens](385819fe-3181-4b7e-b39d-a406d1251231)


			[https://github.com/Outfitio/Outfit-Fonts](https://github.com/Outfitio/Outfit-Fonts)


		[https://www.uifrommars.com/como-escoger-tipografias](https://www.uifrommars.com/como-escoger-tipografias/)


		Google fonts combination [https://femmebot.github.io/google-type](https://femmebot.github.io/google-type/)


		**Open Source Typography Principles** [https://github.com/AlaskaLabs/typography](https://github.com/AlaskaLabs/typography)


		[Adobe® Edge Web Fonts](https://edgewebfonts.adobe.com/fonts)


		[https://zellwk.com/blog/viewport-based-typography/](https://zellwk.com/blog/viewport-based-typography/)


		[Fontello - icon fonts generator](http://fontello.com/)


		[font squirrel](http://www.fontsquirrel.com/)


		[Top 50 Best Free Fonts](http://theultralinx.com/2013/07/top-50-free-fonts.html)


		[Descargar fuentes | dafont.com](http://www.dafont.com/es/)


		[flipping typical](http://flippingtypical.com/)


		[I love Typography](http://ilovetypography.com/)


		[Font Burner](http://www.fontburner.com/)


		[typecast.com](http://typecast.com/)


		[Descargar fuentes | dafont.com](http://www.dafont.com/es/)


		[fontastic.me](http://fontastic.me/)


		[High Quality Decorative Fonts - Alt Foundry](http://alt-foundry.com/)


		[Fontspring. Worry-free fonts for everyone.](https://www.fontspring.com/)


		[Awesome Fontstacks](http://awesome-fontstacks.com/)


		[Las mejores tipografías gratis de 2012 - CSSBlog ES](http://www.cssblog.es/las-mejores-tipografias-gratis-de-2012/)


		[50 nuevas tipografías gratis de alta calidad - CSSBlog ES](http://www.cssblog.es/50-nuevas-tipografias-gratis-de-alta-calidad/)


		[Top Google Web Fonts - Designer First](http://designerfirst.com/blog/top-google-web-fonts/)


		[Google Fonts Source Sans Pro](http://www.google.com/fonts/specimen/Source+Sans+Pro)


		[Typetester – Compare fonts for the screen](http://www.typetester.org/)


	[Design systems](ea8ceb8b-2e10-4c9b-8e26-01798ccba8cb)


		Welcome UI [http://welcome-ui.com](http://welcome-ui.com/)


		Braid Design System [https://seek-oss.github.io/braid-design-system](https://seek-oss.github.io/braid-design-system/)


		Chakra UI [https://chakra-ui.com](https://chakra-ui.com/)


		KITT [http://engineering.typeform.com/kitt](http://engineering.typeform.com/kitt/)


		sampler [https://engineering.typeform.com/sampler](https://engineering.typeform.com/sampler/?path=/story/*)


		Lightning Design System [https://react.lightningdesignsystem.com](https://react.lightningdesignsystem.com/)


		Module Design System [https://radix.modulz.app](https://radix.modulz.app/docs/getting-started/)


		[https://style.geist-ui.dev](https://style.geist-ui.dev/)


		mantine [https://mantine.dev](https://mantine.dev/)


	[Free HTML Templates](565489d9-1e25-4833-8be7-dd0ee8760742)


		html5up.net


		templated.co


		freehtml5.co


		mobirise.com


		uideck.com


	[Color](667ab78b-a1a6-4cb3-abf8-d0f4227dd57d)


		[Tools](ab10367a-1e26-4300-90aa-231a7929e969)


			[Color Scheme Designer 3](http://colorschemedesigner.com/)


			[colourcode - find your colour scheme](http://colourco.de/)


			[color.hailpixel.com · Swatch you doing?](http://color.hailpixel.com/)


			[Colours](http://webcolourdata.com/)


			[Pictaculous - A Color Palette Generator (courtesy of MailChimp)](http://www.pictaculous.com/)


			[Color Hunt](http://colorhunt.co/)


			[Coleure](http://coleure.com/)


			[Adobe Kuler](https://kuler.adobe.com/)


		[https://github.blog/2022-06-14-accelerating-github-theme-creation-with-color-tooling/](https://github.blog/2022-06-14-accelerating-github-theme-creation-with-color-tooling/)


	[Snapshots](81bb7a9a-04fd-4d82-90ba-2ffc11eb7d0d)


		[Blogs](0dd3596c-fb19-4584-beb2-932ffa1af1c1)


		[Footers](1919ac92-890b-4cf2-9876-50cb262bcff4)


		[Colors](0bf043a8-4093-45a3-ad30-e44ed08e9bfc)


		[Logos](71c07455-cbb7-42e6-b360-94afd386b234)


		[Landing](08c7da76-aa46-49eb-aebd-d62d5fe02658)


		[Typos](b2e2fd73-fded-4b72-a03d-1dc9985a3e53)


			![](https://s3.us-west-2.amazonaws.com/secure.notion-static.com/6398f8e2-ac1a-4eea-a425-67f8077119c5/IMG_1017.png?X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Content-Sha256=UNSIGNED-PAYLOAD&X-Amz-Credential=AKIAT73L2G45EIPT3X45%2F20220725%2Fus-west-2%2Fs3%2Faws4_request&X-Amz-Date=20220725T091422Z&X-Amz-Expires=3600&X-Amz-Signature=da2facb358da30398aa54782d7c20fb47cb4d93bb1035dce09411165ae5e29fe&X-Amz-SignedHeaders=host&x-id=GetObject)


			![](https://s3.us-west-2.amazonaws.com/secure.notion-static.com/224f7ad6-4c0a-4db2-a81c-c3f0f228ac21/IMG_1016.png?X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Content-Sha256=UNSIGNED-PAYLOAD&X-Amz-Credential=AKIAT73L2G45EIPT3X45%2F20220725%2Fus-west-2%2Fs3%2Faws4_request&X-Amz-Date=20220725T091422Z&X-Amz-Expires=3600&X-Amz-Signature=2256ed97e9fd52dc9a4edae57f2e081c56f0c0422af8a85f89e729cee0917562&X-Amz-SignedHeaders=host&x-id=GetObject)


			![](https://s3.us-west-2.amazonaws.com/secure.notion-static.com/6a9c0e53-1a7b-445f-9c56-8dd29d74274d/IMG_1015.png?X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Content-Sha256=UNSIGNED-PAYLOAD&X-Amz-Credential=AKIAT73L2G45EIPT3X45%2F20220725%2Fus-west-2%2Fs3%2Faws4_request&X-Amz-Date=20220725T091422Z&X-Amz-Expires=3600&X-Amz-Signature=23494c2cec3bce96915be4d3a3936d78d230b5b317e52839c5d73bed1315409b&X-Amz-SignedHeaders=host&x-id=GetObject)


		[Wallpapers](ab413b3a-b65b-4216-a527-6a7a5e4a7902)


			![](https://s3.us-west-2.amazonaws.com/secure.notion-static.com/142de6f1-d231-4bba-b0d8-bf7e64d32cc0/IMG_0035.jpg?X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Content-Sha256=UNSIGNED-PAYLOAD&X-Amz-Credential=AKIAT73L2G45EIPT3X45%2F20220725%2Fus-west-2%2Fs3%2Faws4_request&X-Amz-Date=20220725T091423Z&X-Amz-Expires=3600&X-Amz-Signature=371d5ec9bea75dad5d695991edcc4175abb49cea1be9edffecdedf2a48152d1c&X-Amz-SignedHeaders=host&x-id=GetObject)
			
			![](https://s3.us-west-2.amazonaws.com/secure.notion-static.com/d85117f4-4bd9-4663-9582-8d650482cdc3/IMG_0025_copy.png?X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Content-Sha256=UNSIGNED-PAYLOAD&X-Amz-Credential=AKIAT73L2G45EIPT3X45%2F20220725%2Fus-west-2%2Fs3%2Faws4_request&X-Amz-Date=20220725T091423Z&X-Amz-Expires=3600&X-Amz-Signature=9b65b51510a9a43190a9af40d561126f7fb7154b5cb0fce649cfff2ee9e82a04&X-Amz-SignedHeaders=host&x-id=GetObject)


			![](https://s3.us-west-2.amazonaws.com/secure.notion-static.com/1a06f0ad-9190-449d-ae22-bd24f51e47bb/IMG_0034.jpg?X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Content-Sha256=UNSIGNED-PAYLOAD&X-Amz-Credential=AKIAT73L2G45EIPT3X45%2F20220725%2Fus-west-2%2Fs3%2Faws4_request&X-Amz-Date=20220725T091423Z&X-Amz-Expires=3600&X-Amz-Signature=a2028c6d384f86ab2341f6c2c2f8c4d2378a89f3a5b6002279b409fbe375ac7c&X-Amz-SignedHeaders=host&x-id=GetObject)


			![](https://s3.us-west-2.amazonaws.com/secure.notion-static.com/18e2d0b7-3e7f-4556-9e14-d3ba70afe04f/IMG_0033.jpg?X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Content-Sha256=UNSIGNED-PAYLOAD&X-Amz-Credential=AKIAT73L2G45EIPT3X45%2F20220725%2Fus-west-2%2Fs3%2Faws4_request&X-Amz-Date=20220725T091423Z&X-Amz-Expires=3600&X-Amz-Signature=3978def470519ba1997f6901d98c5e8f03337f8c66ca092629a2d17ee59ade07&X-Amz-SignedHeaders=host&x-id=GetObject)


			![](https://s3.us-west-2.amazonaws.com/secure.notion-static.com/8f60e97d-e06b-434f-a11e-7b69423c9d6a/IMG_0032.jpg?X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Content-Sha256=UNSIGNED-PAYLOAD&X-Amz-Credential=AKIAT73L2G45EIPT3X45%2F20220725%2Fus-west-2%2Fs3%2Faws4_request&X-Amz-Date=20220725T091423Z&X-Amz-Expires=3600&X-Amz-Signature=4064a543cd28b98a9b0948c3db7a67ee4d2664e2f9d0b15306e583ac0dfcef60&X-Amz-SignedHeaders=host&x-id=GetObject)


			![](https://s3.us-west-2.amazonaws.com/secure.notion-static.com/13921de9-6003-42e6-be21-dda9440f334a/IMG_0031.jpg?X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Content-Sha256=UNSIGNED-PAYLOAD&X-Amz-Credential=AKIAT73L2G45EIPT3X45%2F20220725%2Fus-west-2%2Fs3%2Faws4_request&X-Amz-Date=20220725T091423Z&X-Amz-Expires=3600&X-Amz-Signature=54218a246e73a44291ca583e5c087463d386e0bf16555b909fcc70dfb15d3161&X-Amz-SignedHeaders=host&x-id=GetObject)


			![](https://s3.us-west-2.amazonaws.com/secure.notion-static.com/7b3a1176-c0dc-4769-93ae-eed149a8d5c8/IMG_0030.jpg?X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Content-Sha256=UNSIGNED-PAYLOAD&X-Amz-Credential=AKIAT73L2G45EIPT3X45%2F20220725%2Fus-west-2%2Fs3%2Faws4_request&X-Amz-Date=20220725T091423Z&X-Amz-Expires=3600&X-Amz-Signature=c3265af32e3efbceb7e23d1c4880e1a547aec9c90f7cde245a1859ddc7c06854&X-Amz-SignedHeaders=host&x-id=GetObject)


	[Experience](1cb41d33-8123-4c5b-83bb-cfd6cdfd6773)


		Hooked


		A Survey of Addictive Software Design [https://digitalcommons.calpoly.edu/cgi/viewcontent.cgi?referer=https://scholar.google.co.uk/&httpsredir=1&article=1127&context=cscsp](https://digitalcommons.calpoly.edu/cgi/viewcontent.cgi?referer=https://scholar.google.co.uk/&httpsredir=1&article=1127&context=cscsp)


	[Logos](cbc5b609-fd64-4d7e-bc69-991f970a7607)


		[Logo Of The Day - Logo Design Inspiration, Gallery & Award Scheme!](http://logooftheday.com/)


		[Logo Ideas Gallery | LogoFury.com](http://logofury.com/)


		[logogallery.net - logo inspiration gallery | Logo inspiration gallery.](http://www.logogallery.net/)


		[Logopond - Identity Inspiration](http://logopond.com/)


		[Logoed](http://www.logoed.co.uk/)


		[Logo Design Love](http://www.logodesignlove.com/)


[Human](b207e640-4da4-4da3-a30e-9f6b53867160)


	[Procastination](0ce47c39-6624-480a-9829-a7836771a435)


		[My procrastination cheatsheet](0f417eb1-896f-488d-b30b-238a58056b89)


			My procrastination cheatsheet


			What is? [https://lobste.rs/s/f2sdfz/what_is_procrastination_exactly](https://lobste.rs/s/f2sdfz/what_is_procrastination_exactly)


			
			A while back, I realised that a really effective way of dealing with procrastination is to diagnose the reason that I'm doing it in the first place, rather than blaming myself for not being disciplined enough. Most often, it's not an issue with will-power or discipline, but something else is getting in the way. If I know why I'm procrastinating, I can take steps to make the task easier for myself, choose a different approach, or know when to walk away when I'm not making progress.


			
			So I came up with the Procrastination Cheatsheet as a reference for whenever I've found myself procrastinating. These reflect the most common reasons that I personally procrastinate, so they're not exhaustive. I wanted to share this in case others find it useful.
			



			[Procastination cheatsheet
			](6f13e637-b2df-488b-a0dd-21834b4ae66a)


		**How to stop procrastination** [https://twitter.com/SahilBloom/status/1489968127588851724?s=20&t=KHRpwiZHlnuQ9WigOC1p-w](https://twitter.com/SahilBloom/status/1489968127588851724?s=20&t=KHRpwiZHlnuQ9WigOC1p-w)


	[Relationship](6ff89782-422d-4cf5-b675-af11fa15cae4)


		1. Don’t listen to your friends and relatives, and their opinions about who you should be with. They’re not you and don’t know what you need.
		2. Do listen to your friends and relatives when they say your partner treats you mean. They don’t know what you need, but they notice the things you don’t want to see.


		3. Relationship takes work. You’re both going to adjust to each other throughout the whole time you’re together. Sometimes, you’re going to annoy the hell out of each other.


		4. If all you ever hear or say is that relationship takes work, beware. “We need to make it work” is a huge fucking warning sign, coming from either of you. Need why? Look deeper.


		5. Liking the same things is a terrible signal for whether to form a relationship. If you want to be unhappy, marry your closest [http://Last.fm](http://last.fm/) match.


		6. Some days you might talk for hours, other days you might barely exchange a word. In a happy relationship, both feel good.


		7. Where there is pity or envy, there cannot be respect. Without respect, there is no friendship. Without friendship, there is no love.


		8. You’ll learn more about your relationship in two weeks after moving in together than during two years before that. Delaying that is an irresponsible waste of time for both of you.


		9. It there’s a nagging feeling that something is wrong, something is wrong.


		10. Soulmates are bullshit. They’re not “the one”. But this doesn’t mean you can get along with anyone. You need alignment on two things: Values and Vibe.


		11. You’re aligned on Vibe when both talking and sitting in silence feels good. You’re aligned on Values when you both agree what “good” means in life. Vibe is micro. Values is macro.


		12. You’re going to hate each other’s guts sometimes. But in a loving way.


		13. In a good relationship, there is no shame. You can let out a fart if you want. But there is also a personal space. Neither of you has to share everything.


		14. In fights, you need to learn and respect each other’s coping mechanisms. If someone needs to go out and walk a few miles, that’s cool. If the other person wants to crawl in bed and not talk for the rest of the day, that’s cool too. Give each other the space to calm down.


		15. The media portrayal of happy relationships really screws with our minds. For example, you don’t have to take every vacation together! It’s okay to take a break from each other, explore the world independently, and then share the fun things you found.


		16. It’s okay to want to have kids. It’s also okay to not want to have kids. You probably want to discuss this sooner rather than later.


		17. We already have Values and Vibe, so let’s add Vision and make it three Vs. Where do you both see yourselves in ten years? There might be things to figure out (e.g. disagreements on living in the city vs country), but you need to at least be able to have that conversation.


		18. If you only ever talk about plans, something’s amiss. If you’re waiting for a relationship to get better after some arbitrary point (graduation? new job? move?), notice that the target keeps changing and is always just out of reach. We fool ourselves best.


		19. Being alone is much better than being in a relationship primarily because you don’t want to be alone again.


		20. If one of you needs warmth and physical affection and the other one can’t give or receive it, it’s not gonna work. Sorry.


		21. Vibe includes a shared sense of humor. If you don’t have much intersection there, it’s gonna be tough. Values include a similar attitude towards money. This doesn’t mean coming from the same economic background — but it means a shared sense of what’s okay to spend on what.


		24. Gossiping together is good. It means you trust each other.


		25. A fight getting physical is a huge breach of trust and a good reason to end the relationship.


		26. You don’t need to “earn” happiness by suffering. For example, both I and my wife are happy in our current relationship. But her past experiences have been way more positive than mine. I wish someone taught me better when I was younger.


	[Personal](49b69da0-6272-49fc-bfda-5412d25e905c)

		- The Tail End [https://waitbutwhy.com/2015/12/the-tail-end.html](https://waitbutwhy.com/2015/12/the-tail-end.html)
		- The Lessons of History by Will and Ariel Durant
		- Meditations by Marcus Aurelius
		- Manual for Living by Epictetus
		- A Calendar of Wisdom by Leo Tolstoy
		- Ethereum Wiki [https://github.com/ethereum/wiki/wiki/White-Paper](https://github.com/ethereum/wiki/wiki/White-Paper)
		- The Egg [http://www.galactanet.com/oneoff/theegg_mod.html](http://www.galactanet.com/oneoff/theegg_mod.html)
		- A Dozen Things I’ve Learned from Charlie Munger about Mental Models and Worldly Wisdom [https://25iq.com/2015/08/22/a-dozen-things-ive-learned-from-charlie-munger-about-mental-models-and-worldly-wisdom/](https://25iq.com/2015/08/22/a-dozen-things-ive-learned-from-charlie-munger-about-mental-models-and-worldly-wisdom/)
		- The New 95 [https://medium.com/1517/a-new-95-ec071200d98f](https://medium.com/1517/a-new-95-ec071200d98f)
		- PETER THIEL'S RELIGION [https://www.perell.com/blog/peter-thiel](https://www.perell.com/blog/peter-thiel)
		- How To Be Successful [https://blog.samaltman.com/how-to-be-successful](https://blog.samaltman.com/how-to-be-successful)
		- The Feedback Fallacy [https://hbr.org/2019/03/the-feedback-fallacy](https://hbr.org/2019/03/the-feedback-fallacy)
		- The Use of Knowledge in Society [https://www.econlib.org/library/Essays/hykKnw.html](https://www.econlib.org/library/Essays/hykKnw.html)
		- Speed as a Habit [https://firstround.com/review/speed-as-a-habit/](https://firstround.com/review/speed-as-a-habit/)
		- Memento Mori [https://medium.com/@Jos91/memento-mori-how-remembering-your-mortality-improves-your-life-b056036b76db](https://medium.com/@Jos91/memento-mori-how-remembering-your-mortality-improves-your-life-b056036b76db)
		- Integrity is a matter of a person’s word – nothing more and nothing less. [https://www.dropbox.com/s/e4ajcujlg2yi6rc/Integrity_Without_It_Nothing_Works.pdf?dl=0](https://www.dropbox.com/s/e4ajcujlg2yi6rc/Integrity_Without_It_Nothing_Works.pdf?dl=0)
		- How Superhuman Built an Engine to Find Product/Market Fit [https://firstround.com/review/how-superhuman-built-an-engine-to-find-product-market-fit/](https://firstround.com/review/how-superhuman-built-an-engine-to-find-product-market-fit/)
		- Quantum Thinking [https://medium.com/pronouncedkyle/quantum-thinking-a-new-mental-superpower-as-explained- by-huge-nerds-1641cfd8e7f9](https://medium.com/pronouncedkyle/quantum-thinking-a-new-mental-superpower-as-explained-by-huge-nerds-1641cfd8e7f9)
		- The empty brain [https://aeon.co/essays/your-brain-does-not-process-information-and-it-is-not-a-computer](https://aeon.co/essays/your-brain-does-not-process-information-and-it-is-not-a-computer)
		- 6 Harsh Truths That Will Make You a Better Person [https://www.cracked.com/blog/6-harsh-truths-that-will-make-you-better-person](https://www.cracked.com/blog/6-harsh-truths-that-will-make-you-better-person/)
		- On Connecting [https://medium.com/@dustinfarivar/on-connecting-6b748ade09a3](https://medium.com/@dustinfarivar/on-connecting-6b748ade09a3)
		- The Psychology of Money [https://www.collaborativefund.com/blog/the-psychology-of-money/](https://www.collaborativefund.com/blog/the-psychology-of-money/)

	[Focus](10ef72d8-3f67-4695-86a8-3ecf775d91b9)


		[Time is gold](95fffd2a-18be-46a7-a0b3-3d84ca196735)


			We all have the same 24 hours. It is possibly the ONLY asset that is distributed equally amoungst every human on earth. Everyone you know, that you are inspired by, awed by, jealous ofhas the same 24 hours.It isn't about time
			
			It something else, Here is my take on it...

			- Time is an allocatior
			- Time is energy
			- Time is money

			### Core Idea No. 1


			## Time is an allocation


			We have all heard of the famous Urgent-Important matrix of time. I recall reading it first in school, in the book "7 habits of highly effective people" and being blown away back then by its simplicityIt basically said...


			Depending on whether something is urgent or not and important or not, you either drop, delegate, schedule or do things right away.It worked for me, until it didn't...


			![](https://pbs.twimg.com/media/Ecix08JXYAAoObq.jpg)


			What if I wanted to spend time with a friend, which is neither urgent nor important or maybe watch a movieIf something is not urgent but important AND it won't take a lot of time to finish, why should I schedule it and not do it right away? The model felt incomplete...


			And that is when I changed my approach towards timeI began to do whatever I wanted to do, during a day.And I began measuring. Obsessively measuring. Back in school, I used to record every hour of my day on a notebookWhat did I do and which quadrant did it lie in...


			Unfortunately I lost all of those notebooks to termite (yeah, I know!) Thankfully I moved to digital records back in 2005, when I joined ISB, Here are 2 screenshots
			Tells me I saw "Scent of a woman" one random October day in 2005 :) Here is the key part...


			![](https://pbs.twimg.com/media/Eci0I5gWsAAC2tb.png)


			![](https://pbs.twimg.com/media/Eci0KLwWsAAjOZC.png)


			This measurement was NEVER to reach a target. Instead, it was for a distribution to emerge. A distribution that maximized my performance, my energy and my attention. Here is my current schedule during the lockdownand this is what my distribution looks like...


			![](https://pbs.twimg.com/media/Eci05Y2XoAAow8U.jpg)


			In a week, of my waking hours, I spend 13% of my time on things that are not urgent + not imp 52% of my time on Imp but not urgent 12% on urgent but not imp 23% on things that are both urgent and imp. This is a derivation. Not a target. This is an outcome. It wasn't my goal.


			I got to know of this distribution for the first while preparing for a course on Time Management. And it was fascinating, yet not surprising, to see this split emerge. This distribution allows me to NOT feel guilty about covering all 4 quadrants.And maximizes my productivity


			And how does it maximize my productivity?Because this time distribution maximizes my energy... Which brings me to the 2nd core idea


			## Time is energy


			When people say I do not have time, what they are essentially saying is that I do not have energy.

			- Physical energy
			- Emotional energy
			- Mental energy
			- Spiritual energy

			One's desire to manages time, is one's attempt to manage their energy.


			### Physical energy


			Quality of your sleep. When and what do you eat. Your fitness.


			### Emotional energy


			Do you have self confidence? Do you talk positively to your own self?


			### Mental energy


			Are you creative? Are you optimistic?


			### Spiritual energy


			Do you have integrity, commitment? Honesty?


			If you eat shit and sleep late and lie to yourself that you will fix it tomorrowIt doesn't matter how well you have scheduled yourself for the next dayYour day will be shitty!It isn't about managing timeIt is about managing your energy


			So the key is:


			What distribution of my time across these 4 quadrants of urgent-important maximizes my energy?And thus maximized my productivity. My performance.


			### Core Idea No.3


			## Time is money


			25 years back, I used to spend a day in a wholesale market buying books, to save Rs. 10020 years back, I used to download my music to save money. 15 years back, I visited 10+ showrooms to buy a car at the best price.


			The only goal in life is to keep increasing the value of your time. Everyone's time has a value. If you earn a salary, there is a value of every hour of yours. But we act as if our time is unlimited and thus cheap.


			If you earn 50K per month and work for 22 days for 8 hours a day, your per hour is Rs. 284. So if you watch Netflix for an hour a day, the actual cost of Netflix is not 499 per month. It is 9,000 per month!


			"But I wasn't working for this hour. So how can you say I could have earned and lost this opportunity?"


			Because you could have spent that time in increasing the value of your time. Something we do not actively think of about time more than most people I know and he speaks a lot about the money value of time. He thinks most of India's low respect for time stems from our upbringing where we never had jobs that paid us hourly wages as kids. I agree.


			I have had a beautiful relationship with time and have been fortunate that something early on propelled me to think of as a depleting asset.Think about itIt doesn't matter how much money you have. You can NEVER buy time.


			And yet, we waste time like we will live forever. If you had Rs. 86,400 you wouldn't waste all of it if someone stole Rs. 400 from you, right? And yet we do that everyday. If someone messes us up for 400 seconds, we spend the rest of the day overthinking about it.


		[https://wiki.nikitavoloboev.xyz/focusing/rules](https://wiki.nikitavoloboev.xyz/focusing/rules)


		[https://css-tricks.com/prioritizing/](https://css-tricks.com/prioritizing/)


		[https://blackboxofpm.com/product-management-mental-models-for-everyone-31e7828cb50b](https://blackboxofpm.com/product-management-mental-models-for-everyone-31e7828cb50b)


	[Mindset](d9d288f4-a8bf-4c9c-a9a0-f9d1cc857c8e)


		[Pragmatism and imperfectionism](fa93f326-b0a8-4511-81e4-f14aa686d1fe)


			## Pragmatism


			
			-   Work in a way this is practical and sensible given the circumstances, even if it's different from the theoretical "ideal way"
			-   Focus on what actually gets the job done for your particular project and case, in a way that's good enough in your context
			-   One size doesn't fit all
			-   See also [It depends](./It-depends.md)
			-   See also [Keep it simple](./Keep-it-simple.md)



			##  Don't expect perfection


			
			Programming is hard and people are not perfect, so don't expect perfection.
			
			-   Don't expect perfection from **yourself**
			    -   Just like any other human, you are not perfect
			    -   You will write code that is not bug-free
			    -   You will write code that takes shortcuts, doesn't follow some of the project's conventions or is not clear about its intended purpose
			    -   You will solve problems in suboptimal ways
			    -   You will fail to see things that are obvious in hindsight
			    -   You will lack knowledge on some topics that others know a lot more about and that maybe even seem like essential knowledge
			    -   You will communicate in confusing ways or fail to communicate important information
			    -   You will misunderstand your colleagues, even if what they say is sensible and clear
			-   Don't expect perfection from your **colleagues**
			    -   Just like any other human, your colleagues are not perfect
			    -   Everything that's listed above? Your colleagues will do that too.
			-   Don't expect perfection from your **codebase**
			    -   Your codebase was likely written under time pressure and based on changing requirements, with everyone working on it an imperfect human
			    -   There will be technical debt and not all of it will ever get fixed
			    -   There will be things that don't make sense given the current situation but are impossible or impractical to change
			-   Don't expect perfection from your **process**
			    -   There will be communication overhead and misunderstandings
			    -   There will be unclear and changing requirements
			    -   There will be situations where team members are blocking each other
			    -   There will be situations where team members unknowingly perform duplicate or conflicting work
			    -   There will be decisions that later turn out to be suboptimal because you didn't have the right info, knowledge, experience or priorities at the time
			



			Imperfectionist mindset
			



			### Be humble
			
			-   Realize that you are imperfect, just like everyone around you
			    -   See also the previous section
			-   Be open to feedback from others, as it is likely that you can learn something from them or they have noticed something you missed
			-   Embrace the fact that you can learn a lot from the people around you
			    -   There's no need to be the "smartest person in the room"
			



			### Own your mistakes
			



			-   Since you are not perfect, it is expected that you make mistakes
			    -   Mistakes you make in _specific_ situations do not imply that you are not good at what you do _in general_
			    -   It feels great to realize this and get comfortable admitting your mistakes
			-   Rather than trying to hide your mistakes, admit them and give honest information about what happened
			    -   People who admit their mistakes come across as more confident, reliable and relatable than those who pretend to be perfect
			    -   Bonus points if you already have ideas on how to solve the problem
			    -   Bonus points if you can improve your process so the same mistake won't be able to happen again
			-   Instead of ruminating about mistakes you have made, put that time and energy into fixing the situation or preventing the mistake from happening again
			-   If someone in the team makes a mistake, take responsibility as a team
			    -   Naming the person who made a mistake doesn't solve anything, and gives the impression that the team likes to blame individuals instead of taking responsibility
			    -   Remember that everybody makes mistakes. If the process allowed for this mistake to happen, it was a matter of time before someone actually made the mistake, and it could easily have been someone else.
			    -   Solve the issue as a team and improve your process as a team
			
			Relevant article: [So you've made a mistake and it's public...](https://meta.wikimedia.org/wiki/So_you%27ve_made_a_mistake_and_it%27s_public...)
			



			### Focus on what you can control
			
			-   A lot of things are out of your control, meaning it's a waste of energy to stress out over them or try to change them
			-   Instead, focus on what you can control
			-   "Don’t get stuck thinking that you can’t do good work unless something you can’t control changes" (from [Three Growth Strategies for Individual Contributors](https://hackernoon.com/three-growth-strategies-for-individual-contributors-kv4q3zgt))
			



			### Focus on putting in the work rather than on the results
			
			-   Worrying about results steals time and energy that you could otherwise spend on putting in the actual work that is needed to get the results
			-   Reducing the pressure you put on yourself actually helps you perform your tasks more effectively
			-   Focusing less on results doesn't prevent you from getting the results you want, it just takes away the anxiety about not getting those results
			-   Note: This doesn't mean that there's no value in periodically evaluating whether your work generally gives you the kind of results you would expect to see. However, it does mean that there is no value in letting stress about results distract you from doing the work in the first place.
			



			### Prefer incremental improvement over sudden perfection
			
			-   Focus on consistently making progress or adding value
			-   Start from the way things actually are, not from the way you wish they were
			-   Incremental improvement gives you early feedback on whether you're moving in the right direction
			    -   See also [Fail fast](./Fail-fast.md)
			-   Incremental improvement is often a lot more practical than sudden huge changes
			    -   Example: First writing a working "first draft" of the code and then improving its readability can be a lot more effective than trying to write perfectly clean code immediately
			        -   "First make it work, then make it clean"
			    -   Example: When introducing stricter coding standards to an existing project, changing all the existing code is often not practical or justifiable. But, if you apply the new standards whenever you write new code or touch an existing piece of code, all parts of the codebase that are under active development will soon follow the new standards
			-   Big goals are daunting. Instead, break them into small steps and follow the process, focusing on one step at a time.
			-   There is often a compounding where early progress makes future progress easier
			    -   Example: Setting up basic automated linting makes it easy to add more strict/advanced rules later on
			    -   Example: When learning, properly understanding basic concepts makes it a lot easier to understand more advanced concepts later on ([Concepts, not code](./Concepts-not-code.md))
			-   See also [How to Be Great? Just Be Good, Repeatably](https://blog.stephsmith.io/how-to-be-great/)
			



			### Consider going for imperfect action now instead of possibly perfect action in the future
			
			-   Taking a good enough action means improvement, not taking action means no improvement
			    -   "Great is the enemy of good"
			    -   Good code shipped today is often better than perfect code shipped next week
			-   Often, the experience you gain from taking action teaches you a lot more about what works well and what doesn't than just theorizing about what would be the best approach. See also [Quantity Always Trumps Quality](https://blog.codinghorror.com/quantity-always-trumps-quality/)
			    -   For creative problem solving, it might help to separate the process of creation from the process of analyzing what you created and improving. _"You can’t write and edit, or sculpt and polish, or make and analyze at the same time. If you do, the editor stops the creator. While you invent, don’t select. While you sketch, don’t inspect. While you write the first draft, don’t reflect."_ ([source](https://kk.org/thetechnium/68-bits-of-unsolicited-advice/))
			-   Definitely don't wait for perfect circumstances, as they will likely never come
			



			### Focus on solutions rather than problems
			
			-   Software development is all about problem solving
			    -   Your real value is in delivering _solutions_
			-   Often, problems don't even need to be solved in order to make progress despite them
			    -   A lot of problems are not showstoppers
			    -   In a lot of situations, a workaround or partial solution is enough
			    -   Sometimes, it even makes sense to simply ignore the problem
			-   Rather than focusing on the problem, focus on finding possible solutions or at least paths that lead towards possible solutions
			    -   Problems that seem unfixable at first sight are likely to be fixable once you really think about it
			-   Looking at the big picture helps to find solutions or workarounds that may not be obvious if you focus too closely on the problem
			-   Note: All of this doesn't mean that you should start solving before you understand what the actual problem is!
			    -   See also [Keep it simple](./Keep-it-simple.md)
			-   Note: All of this doesn't mean that there is no value in identifying problems!
			    -   Typically, you need to identify a problem before you can solve it
			    -   It can be very valuable to identify the main problems that are limiting your success
			    -   Try to be a _Finder_, someone who identifies important problems and can also recognize if the team is solving the wrong problem because it's just a symptom of another more fundamental problem
			        -   See [The next career step for Senior Software Engineers (that isn’t management)](https://codewithoutrules.com/2018/10/10/beyond-senior-software-engineer/)
			    -   However, once you've found a problem, start moving your focus to actually solving it rather than just getting stressed by its existence
			



			### Make success easier than failure
			
			Basic idea:
			
			-   All humans tend to get lazy and take the easiest route
			    -   This is especially true if they're under some kind of time pressure
			-   Use this to your advantage by making success easier than failure
			    -   Make it so easy to do the right thing that it would actually be _more_ work to do the wrong thing
			    -   If you want to create substantial and persistent change in the way people do things, you need to make sure that the "right way" to do something is also the easiest way for people to achieve their goals. Instead of forcing people to do something, you need to make them _want_ to do it. Otherwise, they will always find a way around it.
			        -   Making the "right way" easier is often about tooling, but training can also have a large impact
			



			Examples:
			
			-   Productivity
			    -   Chop up your tasks until they're so small and well-defined that it's easier (and more fun) to start and complete them than to find excuses for avoiding them
			-   Enforcing coding standards
			    -   Writing up a document with coding standards and then expecting the team to follow them through sheer discipline is not the ideal approach
			    -   Automated formatting checks and linting make it easy to recognize and fix deviations from the standards
			    -   Even better if everyone in the team has their IDE set up so all code is automatically formatted according to the standards whenever a file is saved
			-   Making people write better PR descriptions
			    -   Can make success easier than failure by setting up a PR template where people just need to fill in the blanks
			        -   Can include description of changes, how to test things, ...
			        -   Can also include a checklist (written/adjusted relevant tests, ensured backwards API compatibility, ...) that we want developers to go through before committing their PR
			-   Architectural governance
			    -   Want teams to do incremental rollouts instead of immediately applying new code to all instances or users? Foresee a deployment pipeline where that is the default behavior and where you need to jump through a few hoops to bypass the mechanism.
			    -   Want developers to respect certain boundaries in your modular monolith? Enforce the boundaries programmatically and require thorough reviewing of any changes to the enforced rules.
			



			## Resources
			
			-   [Pragmatic Software Development](https://medium.com/gsoft-tech/pragmatic-software-development-59d12790e422)
			-   [3 Ways Owning Your Mistakes Will Make You Powerful](https://www.entrepreneur.com/article/232417)
			-   [Why you need to own your mistakes](https://www.klipfolio.com/blog/own-your-mistakes)
			-   [How to professionally acknowledge to a client that a former coworker made a mistake in production?](https://workplace.stackexchange.com/questions/159311/how-to-professionally-acknowledge-to-a-client-that-a-former-coworker-made-a-mist)
			-   How to Be an Imperfectionist (book by Stephen Guise)
			-   [Three Growth Strategies for Individual Contributors](https://hackernoon.com/three-growth-strategies-for-individual-contributors-kv4q3zgt)
			-   [How to Be Great? Just Be Good, Repeatably](https://blog.stephsmith.io/how-to-be-great/)
			-   [Quantity Always Trumps Quality](https://blog.codinghorror.com/quantity-always-trumps-quality/)
			-   [68 Bits of Unsolicited Advice](https://kk.org/thetechnium/68-bits-of-unsolicited-advice/)
			-   [Favourite Diff](https://essays.jwatzman.org/essays/favourite-diff.html)
			-   [The next career step for Senior Software Engineers (that isn’t management)](https://codewithoutrules.com/2018/10/10/beyond-senior-software-engineer/)
			-   [Releasing software to the fleet far too quickly broke stuff](http://rachelbythebay.com/w/2020/04/23/rel/) ([comments on Hacker News](https://news.ycombinator.com/item?id=22962830))


			## 


		## General rules

		- Avoid blindly imitating each other
			- Give 10 seconds for each idea before distracting it
		- Acknowledge your feelings
		- Improve your memory with tools
		- Think slowly and methodically

		## Programming related

		- Debugging - Investigating
		- Deduction: Exploring the mindmap and discard arrows/nodes.
		- Induction: Pick an arrow and boost their probability based on "I feel it".
		- Backtracking: You doubt about everyting.
		- Brainstorming: Get different kinds of minds and make them spread ideas, as much as better.
		- [https://httptoolkit.tech/blog/how-to-debug-anything/](https://httptoolkit.tech/blog/how-to-debug-anything/)

	[Happiness](a97fe1c4-60cd-4043-b21a-d016723dfff1)


		 [https://www.youtube.com/watch?v=-gfEjOgxBfI&ab_channel=NYUStern](https://www.youtube.com/watch?v=-gfEjOgxBfI&ab_channel=NYUStern)


		## **A happy childhood goes a long way**


		A happy childhood is correlated with:
		• Better physical health
		• Strong relationships in later life
		• Lower likelihood of depression by 50


		We're all beyond our childhood, but this is helpful information for parents.


		## Time with loved ones has strong positive effects on happiness:

		- Quality of relationships matters more than quantity.
		- However, quantity of time spent with those relationships is vital.
		- Having a spouse, especially in old age, helped a lot with keeping sadness at bay.

		## Nothing is ever as good as bad as it seems


		## Coping strategies really help:


		These include:
		• Altruism
		• Helping the disadvantaged
		• Suppressing negative feelings


		Effective coping strategies were a predictor for better relationships, strong social support, and sharper brains.


		## Lifestyle has a significant impact on well being:


		Those who aged well:
		• Were physically active
		• Didn't smoke or drink much
		• Had low body weight
		• Enjoyed stable marriages


		The relation between money and happiness


		Low < Mid < High, but it tops out. More money is bright and can draw different stories but more money doesn't bring more happiness. It reaches a point and it flat lines.


		## Know when to let go

		- Happier adults were better at letting go of past failures and troubles.
		- They spend more of their time focusing on activities and things that bring them joy.

		Ask your 20ies what range of money you expect in 10 years. If it's the 1%, you would not have balance


		This is the base of evolutionary progress, it's the base of most problems 


		Women have 2 jobs: 

		- Survive
		- Pick the smartest, strongest and fastest seed

		Man have 2 jobs:

		- Survive
		- Spread the seed

		One of the most influential decisions that will mark your life is to choose your partner. Talk about the expectations, where do we want to live, how we want to live.


		Look at every substance in your life and cut it by 2/3, and look what are other components in your life get affected by it. 


		Forgiveness


		If you don't have a minimum level of forgiveness, it would be difficult to sustain long term relations.


		People (and yourself) will fail each other and break those expectations.


	[Feedback](9838f697-66eb-4158-837f-21d0d72bef2a)


		**Framework for feedback that creates behavior change** [https://twitter.com/wes_kao/status/1489992239283683334?s=20&t=DkswyTPedtiS-IkKV5Yp1g](https://twitter.com/wes_kao/status/1489992239283683334?s=20&t=DkswyTPedtiS-IkKV5Yp1g)


	[Cognitive Biases](0c752135-4aa0-4281-ba5d-f484121755d9)


		[https://en.wikipedia.org/wiki/List_of_cognitive_biases](https://en.wikipedia.org/wiki/List_of_cognitive_biases)


		[Questions to avoid bias, overthink, clearness](d6664e68-724f-460a-8882-5f0fc83869de)

			1. **Is This An Opinion Or Fact?**
			2. **Where Did Your Opinion Come From?**
			3. **What Incentives Are At Play?**
			4. **Are You Consuming Useful Information?**
			5. **What Do The Classics Say?**
			6. **What’s The Opposing Argument?**
			7. **To What Degree Is This True?**
			8. **Could You Be Wrong?**
			9. **Are The "Experts" Really Experts?**
			10. **Are YOU Really An Expert?**
			11. **What Are You Afraid Of?**
			12. **What Are Your Biases?**
			13. **Are You Being Intentional?**
			14. **Is There Really A Wrong Answer?**
			15. **Would You Be Proud To Explain This In Public?**
			16. **Can You Write It Down?**
			17. **Does This Really Matter?**
			18. **What Does Your Gut Say?**
			19. **Should You Even Have An Opinion?**

		[Confirmation Bias](6460d771-19b8-4eeb-919d-7319de4d5345)


			The [confirmation bias](https://www.verywellmind.com/what-is-a-confirmation-bias-2795024) is the tendency to listen more often to information that confirms our existing beliefs. Through this bias, people tend to favor information that reinforces the things they already think or believe.


			Examples include:

			- Only paying attention to information that confirms your beliefs about issues such as gun control and global warming
			- Only following people on social media who share your viewpoints
			- Choosing news sources that present stories that support your views
			- Refusing to [listen to the opposing side](https://www.verywellmind.com/what-is-active-listening-3024343)
			- Not considering all of the facts in a logical and rational manner

			There are a few reasons why this happens. One is that only seeking to confirm existing opinions helps limit mental resources we need to use to make decisions. It also helps protect self-esteem by making people feel that their beliefs are accurate.


			People on two sides of an issue can listen to the same story and walk away with different interpretations that they feel validates their existing point of view. This is often indicative that the confirmation bias is working to "bias" their opinions.


			The problem with this is that it can lead to poor choices, an inability to listen to opposing views, or even contribute to [othering](https://www.verywellmind.com/what-is-othering-5084425) people who hold different opinions.


		[Hindsight Bias](c99fa1a1-f48d-4d25-bbbc-de1d8b9f8170)


			The [hindsight bias](https://www.verywellmind.com/what-is-a-hindsight-bias-2795236) is a common cognitive bias that involves the tendency to see events, even random ones, as more predictable than they are. It's also commonly referred to as the "I knew it all along" phenomenon.


			Some examples of the hindsight bias include:

			- Insisting that you knew who was going to win a football game once the event is over
			- Believing that you knew all along that one political candidate was going to win an election
			- Saying that you knew you weren't going to win after losing a coin flip with a friend
			- Looking back on an exam and thinking that you knew the answers to the questions you missed
			- Believing you could have predicted which stocks would become profitable

			### Classic Research


			In one classic psychology experiment, college students were asked to predict whether they thought then-nominee Clarence Thomas would be confirmed to the U.S. Supreme Court.


			Prior to the Senate vote, 58% of the students thought Thomas would be confirmed. The students were polled again following Thomas's confirmation, and a whopping 78% of students said they had believed Thomas would be confirmed.1


			The hindsight bias occurs for a combination of reasons, including our ability to "misremember" previous predictions, our tendency to view events as inevitable, and our tendency to believe we could have foreseen certain events.


			The effect of this bias is that it causes us to overestimate our ability to predict events. This can sometimes lead people to take unwise risks.


		[Anchoring Bias](e7c58794-4975-4dfb-a3da-55f7977f0c11)


			The [anchoring bias](https://www.verywellmind.com/what-is-the-anchoring-bias-2795029) is the tendency to be overly influenced by the first piece of information that we hear. Some examples of how this works:

			- The first number voiced during a price negotiation typically becomes the anchoring point from which all further negotiations are based.
			- Hearing a random number can influence estimates on completely unrelated topics.2
			- Doctors can become susceptible to the anchoring bias when diagnosing patients. The physician’s [first impressions](https://www.verywellmind.com/person-perception-2795900) of the patient often create an anchoring point that can sometimes incorrectly influence all subsequent diagnostic assessments.3

			While the existence of the anchoring bias is well documented, its causes are still not fully understood. Some research suggests that the source of the anchor information may play a role. Other factors such as priming and mood also appear to have an influence.4


			Like other cognitive biases, anchoring can have an effect on the decisions you make each day. For instance, it can influence how much you are willing to pay for your home. However, it can sometimes lead to poor choices and make it more difficult for people to consider other factors that might also be important.


		[Misinformation Effect](4f7bde55-d0a8-4b3d-83cd-2b15d884b76e)


			The [misinformation effect](https://www.verywellmind.com/what-is-the-misinformation-effect-2795353) is the tendency for memories to be heavily influenced by things that happened after the actual event itself. A person who witnesses a car accident or crime might believe that their recollection is crystal clear, but researchers have found that [memory](https://www.verywellmind.com/what-is-memory-2795006) is surprisingly susceptible to even very subtle influences.


			For example:

			- Research has shown that simply asking questions about an event can change someone's memories of what happened.
			- Watching television coverage may change how people remember the event.
			- Hearing other people talk about a memory from their perspective may change your memory of what transpired.

			### Classic Memory Research


			In one classic experiment by memory expert [Elizabeth Loftus](https://www.verywellmind.com/elizabeth-loftus-biography-2795496), people who watched a video of a car crash were then asked one of two slightly different questions: “How fast were the cars going when they hit each other?” or “How fast were the cars going when they smashed into each other?”5


			When the witnesses were then questioned a week later whether they had seen any broken glass, those who had been asked the “smashed into” version of the question were more likely to report incorrectly that they had seen broken glass.


			There are a few factors that may play a role in this phenomenon. New information may get blended with older memories.6﻿ In other cases, new information may be used to fill in "gaps" in memory.


			The effects of misinformation can range from the trivial to much more serious. It might cause you to misremember something you thought happened at work, or it might lead to someone incorrectly identifying the wrong suspect in a criminal case.


		[Actor-Observer Bias](65522047-72d7-4ab6-9fa4-0a916b85d364)


			The [actor-observer bias](https://www.verywellmind.com/what-is-the-actor-observer-bias-2794813) is the tendency to attribute our actions to external influences and other people's actions to internal ones. The way we perceive others and how we [attribute their actions](https://www.verywellmind.com/attribution-social-psychology-2795898) hinges on a variety of variables, but it can be heavily influenced by whether we are the actor or the observer in a situation.


			When it comes to our own actions, we are often far too likely to attribute things to external influences. For example:

			- You might complain that you botched an important meeting because you had jet lag.
			- You might say you failed an exam because the teacher posed too many trick questions.

			When it comes to explaining other people’s actions, however, we are far more likely to attribute their behaviors to internal causes. For example:

			- A colleague screwed up an important presentation because he’s lazy and incompetent (not because he also had jet lag).
			- A fellow student bombed a test because they lack diligence and intelligence (and not because they took the same test as you with all those trick questions).

			While there are many factors that may play a role, perspective plays a key role. When we are the actors in a situation, we are able to observe our own thoughts and behaviors. When it comes to other people, however, we cannot see what they are thinking. This means we focus on situational forces for ourselves, but guess at the internal characteristics that cause other people's actions.


			The problem with this is that it often leads to misunderstandings. Each side of a situation is essentially blaming the other side rather than thinking about all of the variables that might be playing a role.


		[False Consensus Effect](518421fc-e6ce-49b7-9322-6d715bb247dc)


			The [false consensus effect ](https://www.verywellmind.com/what-is-the-false-consensus-effect-2795030)is the tendency people have to overestimate how much other people agree with their own beliefs, behaviors, attitudes, and values. For example:

			- Thinking that other people share your opinion on controversial topics
			- Overestimating the number of people who are similar to you
			- Believing that the majority of people share your preferences

			Researchers believe that the false consensus effect happens for a variety of reasons. First, the people we spend the most time with, our family and friends, do often tend to share very similar opinions and beliefs. Because of this, we start to think that this way of thinking is the majority opinion even when we are with people who are not among our group of family and friends.


			Another key reason this cognitive bias trips us up so easily is that believing that other people are just like us is good for our [self-esteem](https://www.verywellmind.com/what-is-self-esteem-2795868). It allows us to feel "normal" and maintain a positive view of ourselves in relation to other people.


			This can lead people not only to incorrectly think that everyone else agrees with them—it can sometimes lead them to overvalue their own opinions. It also means that we sometimes don't consider how other people might feel when making choices.


		[Halo Effect](33b9157d-1660-4bf9-88c4-e32f0fd45379)


			The [halo effect](https://www.verywellmind.com/what-is-the-halo-effect-2795906) is the tendency for an initial impression of a person to influence what we think of them overall. Also known as the "[physical attractiveness stereotype](https://www.verywellmind.com/what-is-prejudice-2795476)" or the "what is beautiful is 'good' principle" we are either influenced by or use the halo to influence others almost every day. For example:

			- Thinking people who are good-looking are also smarter, kinder, and funnier than less attractive people
			- Believing that products marketed by attractive people are also more valuable
			- Thinking that a political candidate who is confident must also be intelligent and competent

			One factor that may influence the halo effect is our tendency to want to be correct. If our initial impression of someone was positive, we want to look for proof that our assessment was accurate. It also helps people avoid experiencing [cognitive dissonance](https://www.verywellmind.com/what-is-cognitive-dissonance-2795012), which involves holding contradictory beliefs.


			This cognitive bias can have a powerful impact in the real world. For example, job applicants perceived as attractive and likable are also more likely to be viewed as competent, smart, and qualified for the job.


		[Self-Serving Bias](14932625-cef7-4961-b01c-4c7e8f4a233f)


		[Availability Heuristic](f16526b5-1f07-44ea-9adf-ca9f8905ef1f)


			The [availability heuristic ](https://www.verywellmind.com/availability-heuristic-2794824)is the tendency to estimate the probability of something happening based on how many examples readily come to mind. Some examples of this:

			- After seeing several news reports of car thefts in your neighborhood, you might start to believe that such crimes are more common than they are.
			- You might believe that plane crashes are more common than they really are because you can easily think of several examples.

			It is essentially a mental shortcut designed to save us time when we are trying to determine risk. The problem with relying on this way of thinking is that it often leads to poor estimates and bad decisions.


			Smokers who have never known someone to die of a smoking-related illness, for example, might underestimate the health risks of smoking. In contrast, if you have two sisters and five neighbors who have had breast cancer, you might believe it is even more common than statistics suggest.


		[Optimism Bias](e189787d-7ace-4959-94f2-d1b2314bda22)


			The [optimism bias](https://www.verywellmind.com/what-is-the-optimism-bias-2795031) is a tendency to overestimate the likelihood that good things will happen to us while underestimating the probability that negative events will impact our lives. Essentially, we tend to be too [optimistic](https://www.verywellmind.com/how-to-be-optimistic-4164832) for our own good.


			For example, we may assume that negative events won't affect us such as:

			- Divorce
			- Job loss
			- Illness
			- Death

			The optimism bias has roots in the availability heuristic. Because you can probably think of examples of bad things happening to other people it seems more likely that others will be affected by negative events.


		---


		**Fundamental Attribution Error**


		We judge others on their personality or fundamental character, but we jugde ourselves on the situation. 


		> Sally is late to class, she’s lazy. You’re late to class; it was a bad morning


		---


		**Self serving bias**


		The [self-serving bias ](https://www.verywellmind.com/what-is-the-self-serving-bias-2795032)is a tendency for people tend to give themselves credit for successes but lay the blame for failures on outside causes. When you do well on a project, you probably assume that it’s because you worked hard. But when things turn out badly, you are more likely to blame it on circumstances or bad luck.


		Some examples of this:

		- Attributing good grades to being smart or studying hard
		- Believing your athletic performance is due to practice and hard work
		- Thinking you got the job because of your merits

		The self-serving bias can be influenced by a variety of factors. Age and sex have been shown to play a part. Older people are more likely to take credit for their successes, while men are more likely to pin their failures on outside forces.7


		This bias does serve an important role in protecting self-esteem. However, it can often also lead to faulty attributions such as blaming others for our own shortcomings.


		---


		**In-Group Favoritism**


		We favor people who are in our in-group as opposed to an out-group.


		---


		**Bandwagon Effect**


		Ideas, fads and beliefs grow as more people adopt them.


		---


		**Groupthink**


		Due to a desire for conformity and harmony in the group, we make irrational decisions, often to minimize conflict.


		---


		**Halo Effect**


		If you see a person as having a positive trait, that positive impression will spill over into their other traits. (This also works for negative traits).


		---


		**Moral Luck**


		Better moral standing happens due to a positive outcome; worse moral standing happens due to a negative outcome.


		---


		**False Consensus**


		We believe more people agree with us than is actually the case.


		---


		**Curse of Knowledge**


		Once we know something, we assume everyone else knows it, too.


		---


		**Spotlight Effect**


		We overestimate how much people are paying attention to our behavior and appearance.


		---


		Availability Heuristic: We rely on immediate examples that come to mind while making judgments.


		---


		**Defensive Attribution**


		As a witness who secretly fears being vulnerable to a serious mishap, we will blame the victim less and the attacker more if we relate to the victim.


		---


		Just-World Hypothesis: We tend to believe the world is just; therefore, we assume acts of injustice are deserved.


		---


		Naïve Realism: We believe that we observe objective reality and that others are irrational, uninformed, or biased.


		---


		Naïve Cynicism: We believe that we observe objective reality and that other people have a higher egocentric bias than they actually do in their intentions/actions.


		---


		Forer Effect (aka Barnum Effect): We easily attribute our personalities to vague statements, even if they can apply to a wide range of people.


		---


		Dunning-Kruger Effect: The less you know, the more confident you are. The more you know, the less confident you are.


		---


		Anchoring: We rely heavily on the first information introduced when making decisions.


		---


		Automation Bias: We rely on automated systems, sometimes trusting too much in the automated correction of the actually correct decisions.


		---


		Google effect (aka Digital Amnesia): We tend to forget information that's easily looked up in search engines.


		---


		Reactance: We do the opposite of what we're told, especially when we perceive threats to personal freedoms.


		---


		Confirmation Bias: We tend to find and remember information that confirms our perceptions.


		---


		Backfire Effect: Disproving evidence sometimes has the unwarranted effect of confirming our beliefs.


		---


		Third-Person Effect: We believe that others are more affected by mass media consumption than we ourselves are.


		---


		Belief Bias: We judge an argument's strength not by how strongly it supports the conclusion but how plausible the conclusion is in our own minds.


		---


		Availability Cascade: Tied to our need for social acceptance, collective beliefs gain more plausibility through public repetition.


		---


		Declinism: We tend to romanticize the past and view the future negatively, believing that societies/institutions are by and in large in decline.


		---


		Status Quo Bias: We tend to prefer things to stay the same; changes from the baseline are considered to be a loss.


		---


		Sunk Cost Fallacy (aka Escalation of Commitment): We invest more in things that have cost us something rather than altering our investments, even if we face negative outcomes.


		---


		Gambler's Fallacy: We think future possibilities are affected by past events.


		---


		Zero-Risk Bias: We prefer to reduce small risks to zero, even if we can reduce more risk overall with another option.


		---


		Framing Effect: We often draw different conclusions from the same information depending on how it's presented.


		---


		Stereotyping: We adopt generalized beliefs that members of a group will have certain characteristics, despite not having information about the individual.


		---


		Outgroup Homogeneity Bias: We perceive outgroup members as homogeneous and our own ingroups as more diverse.


		---


		Authority Bias: We trust and are more often influenced by the opinions of authority figures.


		---


		Placebo Effect*: If we believe a treatment will work, it often will have a small physiological effect.


		---


		Survivorship bias: We tend to focus on those things that survived a process and overlook ones that failed.


		---


		Tachypsychia: Our perceptions of time shift depending on trauma, drug use, and physical exertion.


		---


		Law of Triviality (aka "Bike-Shedding"): We give disproportionate weight to trivial issues, often while avoiding more complex issues.


		---


		Zeigarnik Effect: We remember incomplete tasks more than completed ones.


		---


		IKEA Effect: We place higher value on things we have partially created ourselves.


		---


		Ben Franklin Effect: We like doing favors; we are more likely to do another favor for someone if we've already done a favor for them than if we had received a favor from that person.


		---


		Bystander Effect: The more other people are around, the less likely we are to help a victim. (though this technically isn't a cognitive bias, it's another important form of bias, according to TitleMax).


		---


		Suggestibility: We, especially children, sometimes mistake ideas suggested by a questioner for memories.


		---


		False Memory: We mistake imagination for real memories.


		---


		Cryptomnesia: We mistake real memories for imagination.


		---


		Clustering Illusion: We find patterns and "clusters" in random data.


		---


		Pessimism Bias: We sometimes overestimate the likelihood of bad outcomes.


		---


		Optimism Bias: We sometimes are over-optimistic about good outcomes.


		---


		Blind Spot Bias: We don't think we have bias, and we see it in others more than ourselves.


	[Thinking](fb33f0bd-34b0-45e0-85ad-02e57286461e)


		[https://untools.co/thinking-tools-guide/](https://untools.co/thinking-tools-guide/)


	[Public speaking](bc47b65a-b8ed-47ee-aacb-bf9e13a25ac1)


		“In a group of 10,000 people, look for 3 people. One on the left, one on the right and one in the center. Those are your friends. Talk to them and connect with them”


		“Put the anchor words in your slides. Even if people don’t understand what you say, they can look at the slides and make sense out of it”


		“People might hate you, they might like you but you have to be yourself. Don’t worry about your accent and your tone. Just express yourself freely like you express in front of your closed ones”


		“It’s really important to connect with the audience. Start telling a story and make them feel comfortable and interested in whatever you want to present.”


		“Live demos might not work sometimes. That’s fine as long as you know it works. Go ahead and explain what it does”


	[Communication](e379d21a-3718-4619-b7b1-100c64e7edbf)


		[How To Ask Questions The Smart Way](613babef-3391-4bce-b625-6edc940f17c2)


			Eric Steven Raymond [Thyrsus Enterprises](http://www.catb.org/~esr/) [`esr@thyrsus.com`](mailto:esr@thyrsus.com)


			Rick Moen[`respond-auto@linuxmafia.com`](mailto:respond-auto@linuxmafia.com)


			## 


			Translations: [Brazilo-Portuguese](http://blogofscience.com/perguntas.html) [Chinese (Traditional)](https://github.com/ryanhanwu/How-To-Ask-Questions-The-Smart-Way) [Czech](http://scientificachievements.com/jak-se-ptat-chytry-zpusob/) [Dutch](http://docs.jaspervries.nl/smart-questions/) [Estonian](http://glory4cars.com/edu/kuidas-esitada-kusimusi-nutikas-viis/) [French](http://www.gnurou.org/documents/smart-questions-fr.html) [Georgian](http://maxo127.narod.ru/Geo/Articles/smart-questions_ge.html) [German](https://www.privatkreditsofort.ch/wie-man-fragen-richtig-stellt/) [Greek](http://www.dionyziz.com/howto-smart-questions-gr/) [Hindi](http://kntuniversity.org/how-to-ask-questions-the-smart-way/) [Hungarian](http://www.forallworld.com/milyen-kerdeseket-okosan/) [Indonesion](https://www.chameleonjohn.com/translations/smart-questions-Indonesian) [Japanese](http://www.ranvis.com/articles/smart-questions.ja.html) [Lithuanian](http://myscres.com/articles/kaip-uzduoti-klausimus-protinga-buda.html) [Polish](http://rtfm.killfile.pl/) [Portuguese](https://www.homeyou.com/~edu/perguntar-de-forma-inteligente) [Russian](http://maddog.sitengine.ru/smart-question-ru.html) [Spanish](http://www.sindominio.net/ayuda/preguntas-inteligentes.html) [Ukrainian](http://eustudiesweb.com/yak-staviti-zapitannya-rozumno/) [Uzbek](http://www.bestcarzin.com/blog/smart-questions-uzb/) If you want to copy, mirror, translate, or excerpt this document, please see my [copying policy](http://www.catb.org/~esr/copying.html).


			## 


			Many project websites link to this document in their sections on how to get help. That's fine, it's the use we intended — but if you are a webmaster creating such a link for your project page, please display prominently near the link notice that _we are not a help desk for your project!_


			We have learned the hard way that without such a notice, we will repeatedly be pestered by idiots who think having published this document makes it our job to solve all the world's technical problems.


			If you're reading this document because you need help, and you walk away with the impression you can get it directly from the authors of this document, _you_ are one of the idiots we are talking about. Don't ask _us_ questions. We'll just ignore you. We are here to show you how to get help from people who actually know about the software or hardware you're dealing with, but 99.9% of the time that will not be us. Unless you know for _certain_ that one of the authors is an expert on what you're dealing with, leave us alone and everybody will be happier.


			## 


			In the world of [hackers](http://www.catb.org/~esr/faqs/hacker-howto.html), the kind of answers you get to your technical questions depends as much on the way you ask the questions as on the difficulty of developing the answer. This guide will teach you how to ask questions in a way more likely to get you a satisfactory answer.


			Now that use of open source has become widespread, you can often get as good answers from other, more experienced users as from hackers. This is a Good Thing; users tend to be just a little bit more tolerant of the kind of failures newbies often have. Still, treating experienced users like hackers in the ways we recommend here will generally be the most effective way to get useful answers out of them, too.


			The first thing to understand is that hackers actually like hard problems and good, thought-provoking questions about them. If we didn't, we wouldn't be here. If you give us an interesting question to chew on we'll be grateful to you; good questions are a stimulus and a gift. Good questions help us develop our understanding, and often reveal problems we might not have noticed or thought about otherwise. Among hackers, “Good question!” is a strong and sincere compliment.


			Despite this, hackers have a reputation for meeting simple questions with what looks like hostility or arrogance. It sometimes looks like we're reflexively rude to newbies and the ignorant. But this isn't really true.


			What we are, unapologetically, is hostile to people who seem to be unwilling to think or to do their own homework before asking questions. People like that are time sinks — they take without giving back, and they waste time we could have spent on another question more interesting and another person more worthy of an answer. We call people like this “losers” (and for historical reasons we sometimes spell it “lusers”).


			We realize that there are many people who just want to use the software we write, and who have no interest in learning technical details. For most people, a computer is merely a tool, a means to an end; they have more important things to do and lives to live. We acknowledge that, and don't expect everyone to take an interest in the technical matters that fascinate us. Nevertheless, our style of answering questions is tuned for people who _do_ take such an interest and are willing to be active participants in problem-solving. That's not going to change. Nor should it; if it did, we would become less effective at the things we do best.


			We're (largely) volunteers. We take time out of busy lives to answer questions, and at times we're overwhelmed with them. So we filter ruthlessly. In particular, we throw away questions from people who appear to be losers in order to spend our question-answering time more efficiently, on winners.


			If you find this attitude obnoxious, condescending, or arrogant, check your assumptions. We're not asking you to genuflect to us — in fact, most of us would love nothing more than to deal with you as an equal and welcome you into our culture, if you put in the effort required to make that possible. But it's simply not efficient for us to try to help people who are not willing to help themselves. It's OK to be ignorant; it's not OK to play stupid.


			So, while it isn't necessary to already be technically competent to get attention from us, it _is_ necessary to demonstrate the kind of attitude that leads to competence — alert, thoughtful, observant, willing to be an active partner in developing a solution. If you can't live with this sort of discrimination, we suggest you pay somebody for a commercial support contract instead of asking hackers to personally donate help to you.


			If you decide to come to us for help, you don't want to be one of the losers. You don't want to seem like one, either. The best way to get a rapid and responsive answer is to ask it like a person with smarts, confidence, and clues who just happens to need help on one particular problem.


			(Improvements to this guide are welcome. You can mail suggestions to [esr@thyrsus.com](mailto:esr@thyrsus.com) or [respond-auto@linuxmafia.com](mailto:respond-auto@linuxmafia.com). Note however that this document is not intended to be a general guide to [netiquette](http://www.ietf.org/rfc/rfc1855.txt), and we will generally reject suggestions that are not specifically related to eliciting useful answers in a technical forum.)


			## 


			Before asking a technical question by e-mail, or in a newsgroup, or on a website chat board, do the following:


			1. Try to find an answer by searching the archives of the forum or mailing list you plan to post to.
			2. Try to find an answer by searching the Web.
			3. Try to find an answer by reading the manual.
			4. Try to find an answer by reading a FAQ.
			5. Try to find an answer by inspection or experimentation.
			6. Try to find an answer by asking a skilled friend.
			7. If you're a programmer, try to find an answer by reading the source code.


			When you ask your question, display the fact that you have done these things first; this will help establish that you're not being a lazy sponge and wasting people's time. Better yet, display what you have _learned_ from doing these things. We like answering questions for people who have demonstrated they can learn from the answers.


			Use tactics like doing a Google search on the text of whatever error message you get (searching [Google groups](http://groups.google.com/) as well as Web pages). This might well take you straight to fix documentation or a mailing list thread answering your question. Even if it doesn't, saying “I googled on the following phrase but didn't get anything that looked promising” is a good thing to do in e-mail or news postings requesting help, if only because it records what searches won't help. It will also help to direct other people with similar problems to your thread by linking the search terms to what will hopefully be your problem and resolution thread.


			Take your time. Do not expect to be able to solve a complicated problem with a few seconds of Googling. Read and understand the FAQs, sit back, relax and give the problem some thought before approaching experts. Trust us, they will be able to tell from your questions how much reading and thinking you did, and will be more willing to help if you come prepared. Don't instantly fire your whole arsenal of questions just because your first search turned up no answers (or too many).


			Prepare your question. Think it through. Hasty-sounding questions get hasty answers, or none at all. The more you do to demonstrate that having put thought and effort into solving your problem before seeking help, the more likely you are to actually get help.


			Beware of asking the wrong question. If you ask one that is based on faulty assumptions, J. Random Hacker is quite likely to reply with a uselessly literal answer while thinking “Stupid question...”, and hoping the experience of getting what you asked for rather than what you needed will teach you a lesson.


			Never assume you are _entitled_ to an answer. You are not; you aren't, after all, paying for the service. You will earn an answer, if you earn it, by asking a substantial, interesting, and thought-provoking question — one that implicitly contributes to the experience of the community rather than merely passively demanding knowledge from others.


			On the other hand, making it clear that you are able and willing to help in the process of developing the solution is a very good start. “Would someone provide a pointer?”, “What is my example missing?”, and “What site should I have checked?” are more likely to get answered than “Please post the exact procedure I should use.” because you're making it clear that you're truly willing to complete the process if someone can just point you in the right direction.


			## 


			**Choose your forum carefully**


			Be sensitive in choosing where you ask your question. You are likely to be ignored, or written off as a loser, if you:

			- post your question to a forum where it's off topic
			- post a very elementary question to a forum where advanced technical questions are expected, or vice-versa
			- cross-post to too many different newsgroups
			- post a personal e-mail to somebody who is neither an acquaintance of yours nor personally responsible for solving your problem

			Hackers blow off questions that are inappropriately targeted in order to try to protect their communications channels from being drowned in irrelevance. You don't want this to happen to you.


			The first step, therefore, is to find the right forum. Again, Google and other Web-searching methods are your friend. Use them to find the project webpage most closely associated with the hardware or software giving you difficulties. Usually it will have links to a FAQ (Frequently Asked Questions) list, and to project mailing lists and their archives. These mailing lists are the final places to go for help, if your own efforts (including _reading_ those FAQs you found) do not find you a solution. The project page may also describe a bug-reporting procedure, or have a link to one; if so, follow it.


			Shooting off an e-mail to a person or forum which you are not familiar with is risky at best. For example, do not assume that the author of an informative webpage wants to be your free consultant. Do not make optimistic guesses about whether your question will be welcome — if you're unsure, send it elsewhere, or refrain from sending it at all.


			When selecting a Web forum, newsgroup or mailing list, don't trust the name by itself too far; look for a FAQ or charter to verify your question is on-topic. Read some of the back traffic before posting so you'll get a feel for how things are done there. In fact, it's a very good idea to do a keyword search for words relating to your problem on the newsgroup or mailing list archives before you post. It may find you an answer, and if not it will help you formulate a better question.


			Don't shotgun-blast all the available help channels at once, that's like yelling and irritates people. Step through them softly.


			Know what your topic is! One of the classic mistakes is asking questions about the Unix or Windows programming interface in a forum devoted to a language or library or tool portable across both. If you don't understand why this is a blunder, you'd be best off not asking any questions at all until you get it.


			In general, questions to a well-selected public forum are more likely to get useful answers than equivalent questions to a private one. There are multiple reasons for this. One is simply the size of the pool of potential respondents. Another is the size of the audience; hackers would rather answer questions that educate many people than questions serving only a few.


			Understandably, skilled hackers and authors of popular software are already receiving more than their fair share of mis-targeted messages. By adding to the flood, you could in extreme cases even be the straw that breaks the camel's back — quite a few times, contributors to popular projects have withdrawn their support because collateral damage in the form of useless e-mail traffic to their personal accounts became unbearable.


			**Stack Overflow**


			Search, _then_ ask on Stack Exchange


			In recent years, the Stack Exchange community of sites has emerged as a major resource for answering technical and other questions and is even the preferred forum for many open-source projects.


			Start with a Google search before looking at Stack Exchange; Google indexes it in real time. There's a very good chance someone has already asked a similar question, and the Stack Exchange sites are often near the top of the search results. If you didn't find anything through Google, search again on the specific site most relevant to your question (see below). Searching with tags can help narrow down the results.


			If you still didn't find anything, post your question on the _one_ site where it's most on-topic. Use the formatting tools, especially for code, and add tags that are related to the substance of your question (particularly the name of the programming language, operating system, or library you're having trouble with). If a commenter asks you for more information, edit your main post to include it. If any answer is helpful, click the up arrow to upvote it; if an answer gives a solution to your problem, click the check under the voting arrows to accept it as correct.


			Stack Exchange has grown to [over 100 sites](http://stackexchange.com/sites), but here are the most likely candidates:

			- Super User is for questions about general-purpose computing. If your question isn't about code or programs that you talk to only over a network connection, it probably goes here.
			- Stack Overflow is for questions about programming.
			- Server Fault is for questions about server and network administration.

			Several projects have their own specific sites, including Android, Ubuntu, TeX/LaTeX, and SharePoint. Check the Stack Exchange site for an up-to-date list.


			**Web and IRC forums**


			Your local user group, or your Linux distribution, may advertise a Web forum or IRC channel where newbies can get help. (In non-English-speaking countries newbie forums are still more likely to be mailing lists.) These are good first places to ask, especially if you think you may have tripped over a relatively simple or common problem. An advertised IRC channel is an open invitation to ask questions there and often get answers in real time.


			In fact, if you got the program that is giving you problems from a Linux distribution (as is common today), it may be better to ask in the distro's forum/list before trying the program's project forum/list. The project's hackers may just say, “use _our_ build”.


			Before posting to any Web forum, check if it has a Search feature. If it does, try a couple of keyword searches for something like your problem; it just might help. If you did a general Web search before (as you should have), search the forum anyway; your Web-wide search engine might not have all of this forum indexed recently.


			There is an increasing tendency for projects to do user support over a Web forum or IRC channel, with e-mail reserved more for development traffic. So look for those channels first when seeking project-specific help.


			In IRC, it's probably best not to dump a long problem description on the channel first thing; some people interpret this as channel-flooding. Best to utter a one-line problem description in a way pitched to start a conversation on the channel.


			**As a second step, use project mailing lists**


			When a project has a development mailing list, write to the mailing list, not to individual developers, even if you believe you know who can best answer your question. Check the documentation of the project and its homepage for the address of a project mailing list, and use it. There are several good reasons for this policy:

			- Any question good enough to be asked of one developer will also be of value to the whole group. Contrariwise, if you suspect your question is too dumb for a mailing list, it's not an excuse to harass individual developers.
			- Asking questions on the list distributes load among developers. The individual developer (especially if he's the project leader) may be too busy to answer your questions.
			- Most mailing lists are archived and the archives are indexed by search engines. If you ask your question on-list and it is answered, a future querent could find your question and the answer on the Web instead of asking it again.
			- If certain questions are seen to be asked often, developers can use that information to improve the documentation or the software itself to be less confusing. But if those questions are asked in private, nobody has the complete picture of what questions are asked most often.

			If a project has both a “user” and a “developer” (or “hacker”) mailing list or Web forum, and you are not hacking on the code, ask in the “user” list/forum. Do not assume that you will be welcome on the developer list, where they're likely to experience your question as noise disrupting their developer traffic.


			However, if you are _sure_ your question is non-trivial, and you get no answer in the “user” list/forum for several days, try the “developer” one. You would be well advised to lurk there for a few daysor at least review the last few days of archived messages, to learn the local folkways before posting (actually this is good advice on any private or semi-private list).


			If you cannot find a project's mailing list address, but only see the address of the maintainer of the project, go ahead and write to the maintainer. But even in that case, don't assume that the mailing list doesn't exist. Mention in your e-mail that you tried and could not find the appropriate mailing list. Also mention that you don't object to having your message forwarded to other people. (Many people believe that private e-mail should remain private, even if there is nothing secret in it. By allowing your message to be forwarded you give your correspondent a choice about how to handle your e-mail.)


			**Use meaningful, specific subject headers**


			On mailing lists, newsgroups or Web forums, the subject header is your golden opportunity to attract qualified experts' attention in around 50 characters or fewer. Don't waste it on babble like “Please help me” (let alone “PLEASE HELP ME!!!!”; messages with subjects like that get discarded by reflex). Don't try to impress us with the depth of your anguish; use the space for a super-concise problem description instead.


			One good convention for subject headers, used by many tech support organizations, is “object - deviation”. The “object” part specifies what thing or group of things is having a problem, and the “deviation” part describes the deviation from expected behavior.


			**Stupid:**HELP! Video doesn't work properly on my laptop!**Smart:**X.org 6.8.1 misshapen mouse cursor, Fooware MV1005 vid. chipset**Smarter:**X.org 6.8.1 mouse cursor on Fooware MV1005 vid. chipset - is misshapen


			The process of writing an “object-deviation” description will help you organize your thinking about the problem in more detail. What is affected? Just the mouse cursor or other graphics too? Is this specific to the X.org version of X? To version 6.8.1? Is this specific to Fooware video chipsets? To model MV1005? A hacker who sees the result can immediately understand what it is that you are having a problem with _and_ the problem you are having, at a glance.


			More generally, imagine looking at the index of an archive of questions, with just the subject lines showing. Make your subject line reflect your question well enough that the next person searching the archive with a question similar to yours will be able to follow the thread to an answer rather than posting the question again.


			If you ask a question in a reply, be sure to change the subject line to indicate that you're asking a question. A Subject line that looks like “Re: test” or “Re: new bug” is less likely to attract useful amounts of attention. Also, pare quotation of previous messages to the minimum consistent with cluing in new readers.


			Do not simply hit reply to a list message in order to start an entirely new thread. This will limit your audience. Some mail readers, like mutt, allow the user to sort by thread and then hide messages in a thread by folding the thread. Folks who do that will never see your message.


			Changing the subject is not sufficient. Mutt, and probably other mail readers, looks at other information in the e-mail's headers to assign it to a thread, not the subject line. Instead start an entirely new e-mail.


			On Web forums the rules of good practice are slightly different, because messages are usually much more tightly bound to specific discussion threads and often invisible outside those threads. Changing the subject when asking a question in reply is not essential. Not all forums even allow separate subject lines on replies, and nearly nobody reads them when they do. However, asking a question in a reply is a dubious practice in itself, because it will only be seen by those who are watching this thread. So, unless you are sure you _want_ to ask only the people currently active in the thread, start a new one.


			**Make it easy to reply**


			Finishing your query with “Please send your reply to... ” makes it quite unlikely you will get an answer. If you can't be bothered to take even the few seconds required to set up a correct Reply-To header in your mail agent, we can't be bothered to take even a few seconds to think about your problem. If your mail program doesn't permit this, [get a better mail program](http://linuxmafia.com/faq/Mail/muas.html). If your operating system doesn't support any e-mail programs that permit this, get a better operating system.


			In Web forums, asking for a reply by e-mail is outright rude, unless you believe the information may be sensitive (and somebody will, for some unknown reason, let you but not the whole forum know it). If you want an e-mail copy when somebody replies in the thread, request that the Web forum send it; this feature is supported almost everywhere under options like “watch this thread”, “send e-mail on answers”, etc.


			**Write in clear, grammatical, correctly-spelled language**


			We've found by experience that people who are careless and sloppy writers are usually also careless and sloppy at thinking and coding (often enough to bet on, anyway). Answering questions for careless and sloppy thinkers is not rewarding; we'd rather spend our time elsewhere.


			So expressing your question clearly and well is important. If you can't be bothered to do that, we can't be bothered to pay attention. Spend the extra effort to polish your language. It doesn't have to be stiff or formal — in fact, hacker culture values informal, slangy and humorous language used with precision. But it has to _be_ precise; there has to be some indication that you're thinking and paying attention.


			Spell, punctuate, and capitalize correctly. Don't confuse “its” with “it's”, “loose” with “lose”, or “discrete” with “discreet”. Don't TYPE IN ALL CAPS; this is read as shouting and considered rude. (All-smalls is only slightly less annoying, as it's difficult to read. Alan Cox can get away with it, but you can't.)


			More generally, if you write like a semi-literate boob you will very likely be ignored. So don't use instant-messaging shortcuts. Spelling "you" as "u" makes you look like a semi-literate boob to save two entire keystrokes. Worse: writing like a l33t script kiddie hax0r is the absolute kiss of death and guarantees you will receive nothing but stony silence (or, at best, a heaping helping of scorn and sarcasm) in return.


			If you are asking questions in a forum that does not use your native language, you will get a limited amount of slack for spelling and grammar errors — but no extra slack at all for laziness (and yes, we can usually spot that difference). Also, unless you know what your respondent's languages are, write in English. Busy hackers tend to simply flush questions in languages they don't understand, and English is the working language of the Internet. By writing in English you minimize your chances that your question will be discarded unread.


			If you are writing in English but it is a second language for you, it is good form to alert potential respondents to potential language difficulties and options for getting around them. Examples:

			- English is not my native language; please excuse typing errors.
			- If you speak $LANGUAGE, please email/PM me; I may need assistance translating my question.
			- I am familiar with the technical terms, but some slang expressions and idioms are difficult for me.
			- I've posted my question in $LANGUAGE and English. I'll be glad to translate responses, if you only use one or the other.

			**Send questions in accessible, standard formats**


			If you make your question artificially hard to read, it is more likely to be passed over in favor of one that isn't. So:

			- Send plain text mail, not HTML. (It's not hard to [turn off HTML](http://www.birdhouse.org/etc/evilmail.html).)
			- MIME attachments are usually OK, but only if they are real content (such as an attached source file or patch), and not merely boilerplate generated by your mail client (such as another copy of your message).
			- Don't send e-mail in which entire paragraphs are single multiply-wrapped lines. (This makes it too difficult to reply to just part of the message.) Assume that your respondents will be reading mail on 80-character-wide text displays and set your line wrap accordingly, to something less than 80.
			- However, do _not_ wrap data (such as log file dumps or session transcripts) at any fixed column width. Data should be included as-is, so respondents can have confidence that they are seeing what you saw.
			- Don't send MIME Quoted-Printable encoding to an English-language forum. This encoding can be necessary when you're posting in a language ASCII doesn't cover, but many e-mail agents don't support it. When they break, all those =20 glyphs scattered through the text are ugly and distracting — or may actively sabotage the semantics of your text.
			- Never, _ever_ expect hackers to be able to read closed proprietary document formats like Microsoft Word or Excel. Most hackers react to these about as well as you would to having a pile of steaming pig manure dumped on your doorstep. Even when they can cope, they resent having to do so.
			- If you're sending e-mail from a Windows machine, turn off Microsoft's problematic “Smart Quotes” feature (From Tools > AutoCorrect Options, clear the smart quotes checkbox under AutoFormat As You Type.). This is so you'll avoid sprinkling garbage characters through your mail.
			- In Web forums, do not abuse “smiley” and “HTML” features (when they are present). A smiley or two is usually OK, but colored fancy text tends to make people think you are lame. Seriously overusing smileys and color and fonts will make you come off like a giggly teenage girl, which is not generally a good idea unless you are more interested in sex than answers.

			If you're using a graphical-user-interface mail client such as Netscape Messenger, MS Outlook, or their ilk, beware that it may violate these rules when used with its default settings. Most such clients have a menu-based “View Source” command. Use this on something in your sent-mail folder, verifying sending of plain text without unnecessary attached crud.


			**Be precise and informative about your problem**

			- Describe the symptoms of your problem or bug carefully and clearly.
			- Describe the environment in which it occurs (machine, OS, application, whatever). Provide your vendor's distribution and release level (e.g.: “Fedora Core 7”, “Slackware 9.1”, etc.).
			- Describe the research you did to try and understand the problem before you asked the question.
			- Describe the diagnostic steps you took to try and pin down the problem yourself before you asked the question.
			- Describe any possibly relevant recent changes in your computer or software configuration.
			- If at all possible, provide a way to _reproduce the problem in a controlled environment_.

			Do the best you can to anticipate the questions a hacker will ask, and answer them in advance in your request for help.


			Giving hackers the ability to reproduce the problem in a controlled environment is especially important if you are reporting something you think is a bug in code. When you do this, your odds of getting a useful answer and the speed with which you are likely to get that answer both improve tremendously.


			Simon Tatham has written an excellent essay entitled [How to Report Bugs Effectively](http://www.chiark.greenend.org.uk/~sgtatham/bugs.html). I strongly recommend that you read it.


			**Volume is not precision**


			You need to be precise and informative. This end is not served by simply dumping huge volumes of code or data into a help request. If you have a large, complicated test case that is breaking a program, try to trim it and make it as small as possible.


			This is useful for at least three reasons. One: being seen to invest effort in simplifying the question makes it more likely you'll get an answer, Two: simplifying the question makes it more likely you'll get a _useful_ answer. Three: In the process of refining your bug report, you may develop a fix or workaround yourself.


			**Don't rush to claim that you have found a bug**


			When you are having problems with a piece of software, don't claim you have found a bug unless you are very, _very_ sure of your ground. Hint: unless you can provide a source-code patch that fixes the problem, or a regression test against a previous version that demonstrates incorrect behavior, you are probably not sure enough. This applies to webpages and documentation, too; if you have found a documentation “bug”, you should supply replacement text and which pages it should go on.


			Remember, there are many other users that are not experiencing your problem. Otherwise you would have learned about it while reading the documentation and searching the Web (you did do that before complaining, [didn't you](http://www.catb.org/~esr/faqs/smart-questions.html#before)?). This means that very probably it is you who are doing something wrong, not the software.


			The people who wrote the software work very hard to make it work as well as possible. If you claim you have found a bug, you'll be impugning their competence, which may offend some of them even if you are correct. It's especially undiplomatic to yell “bug” in the Subject line.


			When asking your question, it is best to write as though you assume _you_ are doing something wrong, even if you are privately pretty sure you have found an actual bug. If there really is a bug, you will hear about it in the answer. Play it so the maintainers will want to apologize to you if the bug is real, rather than so that you will owe them an apology if you have messed up.


			**Grovelling is not a substitute for doing your homework**


			Some people who get that they shouldn't behave rudely or arrogantly, demanding an answer, retreat to the opposite extreme of grovelling. “I know I'm just a pathetic newbie loser, but...”. This is distracting and unhelpful. It's especially annoying when it's coupled with vagueness about the actual problem.


			Don't waste your time, or ours, on crude primate politics. Instead, present the background facts and your question as clearly as you can. That is a better way to position yourself than by grovelling.


			Sometimes Web forums have separate places for newbie questions. If you feel you do have a newbie question, just go there. But don't grovel there either.


			**Describe the problem's symptoms, not your guesses**


			It's not useful to tell hackers what you think is causing your problem. (If your diagnostic theories were such hot stuff, would you be consulting others for help?) So, make sure you're telling them the raw symptoms of what goes wrong, rather than your interpretations and theories. Let them do the interpretation and diagnosis. If you feel it's important to state your guess, clearly label it as such and describe why that answer isn't working for you.


			**Stupid:**I'm getting back-to-back SIG11 errors on kernel compiles, and suspect a hairline crack on one of the motherboard traces. What's the best way to check for those?**Smart:**My home-built K6/233 on an FIC-PA2007 motherboard (VIA Apollo VP2 chipset) with 256MB Corsair PC133 SDRAM starts getting frequent SIG11 errors about 20 minutes after power-on during the course of kernel compiles, but never in the first 20 minutes. Rebooting doesn't restart the clock, but powering down overnight does. Swapping out all RAM didn't help. The relevant part of a typical compile session log follows.


			Since the preceding point seems to be a tough one for many people to grasp, here's a phrase to remind you: "All diagnosticians are from Missouri." That US state's official motto is "Show me" (earned in 1899, when Congressman Willard D. Vandiver said "I come from a country that raises corn and cotton and cockleburs and Democrats, and frothy eloquence neither convinces nor satisfies me. I'm from Missouri. You've got to show me.") In diagnosticians' case, it's not a matter of skepticism, but rather a literal, functional need to see whatever is as close as possible to the same raw evidence that you see, rather than your surmises and summaries. Show us.


			**Describe your problem's symptoms in chronological order**


			The clues most useful in figuring out something that went wrong often lie in the events immediately prior. So, your account should describe precisely what you did, and what the machine and software did, leading up to the blowup. In the case of command-line processes, having a session log (e.g., using the script utility) and quoting the relevant twenty or so lines is very useful.


			If the program that blew up on you has diagnostic options (such as -v for verbose), try to select options that will add useful debugging information to the transcript. Remember that more is not necessarily better; try to choose a debug level that will inform rather than drowning the reader in junk.


			If your account ends up being long (more than about four paragraphs), it might be useful to succinctly state the problem up top, then follow with the chronological tale. That way, hackers will know what to watch for in reading your account.


			**Describe the goal, not the step**


			If you are trying to find out how to do something (as opposed to reporting a bug), begin by describing the goal. Only then describe the particular step towards it that you are blocked on.


			Often, people who need technical help have a high-level goal in mind and get stuck on what they think is one particular path towards the goal. They come for help with the step, but don't realize that the path is wrong. It can take substantial effort to get past this.


			**Stupid:**How do I get the color-picker on the FooDraw program to take a hexadecimal RGB value?**Smart:**I'm trying to replace the color table on an image with values of my choosing. Right now the only way I can see to do this is by editing each table slot, but I can't get FooDraw's color picker to take a hexadecimal RGB value.


			The second version of the question is smart. It allows an answer that suggests a tool better suited to the task.


			**Don't ask people to reply by private e-mail**


			Hackers believe solving problems should be a public, transparent process during which a first try at an answer can and should be corrected if someone more knowledgeable notices that it is incomplete or incorrect. Also, helpers get some of their reward for being respondents from being seen to be competent and knowledgeable by their peers.


			When you ask for a private reply, you are disrupting both the process and the reward. Don't do this. It's the _respondent's_ choice whether to reply privately — and if he or she does, it's usually because he or she thinks the question is too ill-formed or obvious to be interesting to others.


			There is one limited exception to this rule. If you think the question is such that you are likely to get many answers that are all closely similar, then the magic words are “e-mail me and I'll summarize the answers for the group”. It is courteous to try and save the mailing list or newsgroup a flood of substantially identical postings — but you have to keep the promise to summarize.


			**Be explicit about your question**


			Open-ended questions tend to be perceived as open-ended time sinks. Those people most likely to be able to give you a useful answer are also the busiest people (if only because they take on the most work themselves). People like that are allergic to open-ended time sinks, thus they tend to be allergic to open-ended questions.


			You are more likely to get a useful response if you are explicit about what you want respondents to do (provide pointers, send code, check your patch, whatever). This will focus their effort and implicitly put an upper bound on the time and energy a respondent must allocate to helping you. This is good.


			To understand the world the experts live in, think of expertise as an abundant resource and time to respond as a scarce one. The less of a time commitment you implicitly ask for, the more likely you are to get an answer from someone really good and really busy.


			So it is useful to frame your question to minimize the time commitment required for an expert to field it — but this is often not the same thing as simplifying the question. Thus, for example, “Would you give me a pointer to a good explanation of X?” is usually a smarter question than “Would you explain X, please?”. If you have some malfunctioning code, it is usually smarter to ask for someone to explain what's wrong with it than it is to ask someone to fix it.


			**When asking about code**


			Don't ask others to debug your broken code without giving a hint what sort of problem they should be searching for. Posting a few hundred lines of code, saying "it doesn't work", will get you ignored. Posting a dozen lines of code, saying "after line 7 I was expecting to see <x>, but <y> occurred instead" is much more likely to get you a response.


			The most effective way to be precise about a code problem is to provide a minimal bug-demonstrating test case. What's a minimal test case? It's an illustration of the problem; just enough code to exhibit the undesirable behavior and no more. How do you make a minimal test case? If you know what line or section of code is producing the problematic behavior, make a copy of it and add just enough supporting code to produce a complete example (i.e. enough that the source is acceptable to the compiler/interpreter/whatever application processes it). If you can't narrow it down to a particular section, make a copy of the source and start removing chunks that don't affect the problematic behavior. The smaller your minimal test case is, the better (see [the section called “Volume is not precision”](http://www.catb.org/~esr/faqs/smart-questions.html#volume)).


			Generating a really small minimal test case will not always be possible, but trying to is good discipline. It may help you learn what you need to solve the problem on your own — and even when it doesn't, hackers like to see that you have tried. It will make them more cooperative.


			If you simply want a code review, say as much up front, and be sure to mention what areas you think might particularly need review and why.


			**Don't post homework questions**


			Hackers are good at spotting homework questions; most of us have done them ourselves. Those questions are for _you_ to work out, so that you will learn from the experience. It is OK to ask for hints, but not for entire solutions.


			If you suspect you have been passed a homework question, but can't solve it anyway, try asking in a user group forum or (as a last resort) in a “user” list/forum of a project. While the hackers _will_ spot it, some of the advanced users may at least give you a hint.


			**Prune pointless queries**


			Resist the temptation to close your request for help with semantically-null questions like “Can anyone help me?” or “Is there an answer?” First: if you've written your problem description halfway competently, such tacked-on questions are at best superfluous. Second: because they are superfluous, hackers find them annoying — and are likely to return logically impeccable but dismissive answers like “Yes, you can be helped” and “No, there is no help for you.”


			In general, asking yes-or-no questions is a good thing to avoid unless you want a [yes-or-no answer](http://homepage.ntlworld.com./jonathan.deboynepollard/FGA/questions-with-yes-or-no-answers.html).


			**Don't flag your question as “Urgent”, even if it is for you**


			That's your problem, not ours. Claiming urgency is very likely to be counter-productive: most hackers will simply delete such messages as rude and selfish attempts to elicit immediate and special attention. Furthermore, the word 'Urgent' (and other similar attempts to grab attention in the subject line) often triggers spam filters - your intended recipients might never see it at all!


			There is one semi-exception. It can be worth mentioning if you're using the program in some high-profile place, one that the hackers will get excited about; in such a case, if you're under time pressure, and you say so politely, people may get interested enough to answer faster.


			This is a very risky thing to do, however, because the hackers' metric for what is exciting probably differs from yours. Posting from the International Space Station would qualify, for example, but posting on behalf of a feel-good charitable or political cause would almost certainly not. In fact, posting “Urgent: Help me save the fuzzy baby seals!” will reliably get you shunned or flamed even by hackers who think fuzzy baby seals are important.


			If you find this mysterious, re-read the rest of this how-to repeatedly until you understand it before posting anything at all.


			**Courtesy never hurts, and sometimes helps**


			Be courteous. Use “Please” and “Thanks for your attention” or “Thanks for your consideration”. Make it clear you appreciate the time people spend helping you for free.


			To be honest, this isn't as important as (and cannot substitute for) being grammatical, clear, precise and descriptive, avoiding proprietary formats etc.; hackers in general would rather get somewhat brusque but technically sharp bug reports than polite vagueness. (If this puzzles you, remember that we value a question by what it teaches us.)


			However, if you've got your technical ducks in a row, politeness does increase your chances of getting a useful answer.


			(We must note that the only serious objection we've received from veteran hackers to this HOWTO is with respect to our previous recommendation to use “Thanks in advance”. Some hackers feel this connotes an intention not to thank anybody afterwards. Our recommendation is to either say “Thanks in advance” first _and_ thank respondents afterwards, or express courtesy in a different way, such as by saying “Thanks for your attention” or “Thanks for your consideration”.)


			**Follow up with a brief note on the solution**


			Send a note after the problem has been solved to all who helped you; let them know how it came out and thank them again for their help. If the problem attracted general interest in a mailing list or newsgroup, it's appropriate to post the followup there.


			Optimally, the reply should be to the thread started by the original question posting, and should have ‘FIXED’, ‘RESOLVED’ or an equally obvious tag in the subject line. On mailing lists with fast turnaround, a potential respondent who sees a thread about “Problem X” ending with “Problem X - FIXED” knows not to waste his/her time even reading the thread (unless (s)he personally finds Problem X interesting) and can therefore use that time solving a different problem.


			Your followup doesn't have to be long and involved; a simple “Howdy — it was a failed network cable! Thanks, everyone. - Bill” would be better than nothing. In fact, a short and sweet summary is better than a long dissertation unless the solution has real technical depth. Say what action solved the problem, but you need not replay the whole troubleshooting sequence.


			For problems with some depth, it is appropriate to post a summary of the troubleshooting history. Describe your final problem statement. Describe what worked as a solution, and indicate avoidable blind alleys _after that_. The blind alleys should come after the correct solution and other summary material, rather than turning the follow-up into a detective story. Name the names of people who helped you; you'll make friends that way.


			Besides being courteous and informative, this sort of followup will help others searching the archive of the mailing-list/newsgroup/forum to know exactly which solution helped you and thus may also help them.


			Last, and not least, this sort of followup helps everybody who assisted feel a satisfying sense of closure about the problem. If you are not a techie or hacker yourself, trust us that this feeling is very important to the gurus and experts you tapped for help. Problem narratives that trail off into unresolved nothingness are frustrating things; hackers itch to see them resolved. The goodwill that scratching that itch earns you will be very, very helpful to you next time you need to pose a question.


			Consider how you might be able to prevent others from having the same problem in the future. Ask yourself if a documentation or FAQ patch would help, and if the answer is yes send that patch to the maintainer.


			Among hackers, this sort of good followup behavior is actually more important than conventional politeness. It's how you get a reputation for playing well with others, which can be a very valuable asset.


			## 


			**RTFM and STFW: How To Tell You've Seriously Screwed Up**


			There is an ancient and hallowed tradition: if you get a reply that reads “RTFM”, the person who sent it thinks you should have Read The Fucking Manual. He or she is almost certainly right. Go read it.


			RTFM has a younger relative. If you get a reply that reads “STFW”, the person who sent it thinks you should have Searched The Fucking Web. He or she is almost certainly right. Go search it. (The milder version of this is when you are told “Google is your friend!”)


			In Web forums, you may also be told to search the forum archives. In fact, someone may even be so kind as to provide a pointer to the previous thread where this problem was solved. But do not rely on this consideration; do your archive-searching before asking.


			Often, the person telling you to do a search has the manual or the web page with the information you need open, and is looking at it as he or she types. These replies mean that the responder thinks (a) the information you need is easy to find, and (b) you will learn more if you seek out the information than if you have it spoon-fed to you.


			You shouldn't be offended by this; by hacker standards, your respondent is showing you a rough kind of respect simply by not ignoring you. You should instead be thankful for this grandmotherly kindness.


			**If you don't understand...**


			If you don't understand the answer, do not immediately bounce back a demand for clarification. Use the same tools that you used to try and answer your original question (manuals, FAQs, the Web, skilled friends) to understand the answer. Then, if you still need to ask for clarification, exhibit what you have learned.


			For example, suppose I tell you: “It sounds like you've got a stuck zentry; you'll need to clear it.” Then: here's a _bad_ followup question: “What's a zentry?” Here's a _good_ followup question: “OK, I read the man page and zentries are only mentioned under the -z and -p switches. Neither of them says anything about clearing zentries. Is it one of these or am I missing something here?”


			**Dealing with rudeness**


			Much of what looks like rudeness in hacker circles is not intended to give offense. Rather, it's the product of the direct, cut-through-the-bullshit communications style that is natural to people who are more concerned about solving problems than making others feel warm and fuzzy.


			When you perceive rudeness, try to react calmly. If someone is really acting out, it is very likely a senior person on the list or newsgroup or forum will call him or her on it. If that _doesn't_ happen and you lose your temper, it is likely that the person you lose it at was behaving within the hacker community's norms and _you_ will be considered at fault. This will hurt your chances of getting the information or help you want.


			On the other hand, you will occasionally run across rudeness and posturing that is quite gratuitous. The flip-side of the above is that it is acceptable form to slam real offenders quite hard, dissecting their misbehavior with a sharp verbal scalpel. Be very, very sure of your ground before you try this, however. The line between correcting an incivility and starting a pointless flamewar is thin enough that hackers themselves not infrequently blunder across it; if you are a newbie or an outsider, your chances of avoiding such a blunder are low. If you're after information rather than entertainment, it's better to keep your fingers off the keyboard than to risk this.


			(Some people assert that many hackers have a mild form of autism or Asperger's Syndrome, and are actually missing some of the brain circuitry that lubricates “normal” human social interaction. This may or may not be true. If you are not a hacker yourself, it may help you cope with our eccentricities if you think of us as being brain-damaged. Go right ahead. We won't care; we _like_ being whatever it is we are, and generally have a healthy skepticism about clinical labels.)


			Jeff Bigler's observations about [tact filters](http://www.mit.edu/~jcb/tact.html) are also relevant and worth reading.


			In the next section, we'll talk about a different issue; the kind of “rudeness” you'll see when _you_ misbehave.


			## 


			Odds are you'll screw up a few times on hacker community forums — in ways detailed in this article, or similar. And you'll be told exactly how you screwed up, possibly with colourful asides. In public.


			When this happens, the worst thing you can do is whine about the experience, claim to have been verbally assaulted, demand apologies, scream, hold your breath, threaten lawsuits, complain to people's employers, leave the toilet seat up, etc. Instead, here's what you do:


			Get over it. It's normal. In fact, it's healthy and appropriate.


			Community standards do not maintain themselves: They're maintained by people actively applying them, visibly, _in public_. Don't whine that all criticism should have been conveyed via private e-mail: That's not how it works. Nor is it useful to insist you've been personally insulted when someone comments that one of your claims was wrong, or that his views differ. Those are loser attitudes.


			There have been hacker forums where, out of some misguided sense of hyper-courtesy, participants are banned from posting any fault-finding with another's posts, and told “Don't say anything if you're unwilling to help the user.” The resulting departure of clueful participants to elsewhere causes them to descend into meaningless babble and become useless as technical forums.


			Exaggeratedly “friendly” (in that fashion) or useful: Pick one.


			Remember: When that hacker tells you that you've screwed up, and (no matter how gruffly) tells you not to do it again, he's acting out of concern for (1) you and (2) his community. It would be much easier for him to ignore you and filter you out of his life. If you can't manage to be grateful, at least have a little dignity, don't whine, and don't expect to be treated like a fragile doll just because you're a newcomer with a theatrically hypersensitive soul and delusions of entitlement.


			Sometimes people will attack you personally, flame without an apparent reason, etc., even if you don't screw up (or have only screwed up in their imagination). In this case, complaining is the way to _really_ screw up.


			These flamers are either lamers who don't have a clue but believe themselves to be experts, or would-be psychologists testing whether you'll screw up. The other readers either ignore them, or find ways to deal with them on their own. The flamers' behavior creates problems for themselves, which don't have to concern you.


			Don't let yourself be drawn into a flamewar, either. Most flames are best ignored — after you've checked whether they are really flames, not pointers to the ways in which you have screwed up, and not cleverly ciphered answers to your real question (this happens as well).


			## 


			Here are some classic stupid questions, and what hackers are thinking when they don't answer them.


			Q: [Where can I find program or resource X?](http://www.catb.org/~esr/faqs/smart-questions.html#idm551)Q: [How can I use X to do Y?](http://www.catb.org/~esr/faqs/smart-questions.html#idm557)Q: [How can I configure my shell prompt?](http://www.catb.org/~esr/faqs/smart-questions.html#idm562)Q: [Can I convert an AcmeCorp document into a TeX file using the Bass-o-matic file converter?](http://www.catb.org/~esr/faqs/smart-questions.html#idm568)Q: [My {program, configuration, SQL statement} doesn't work](http://www.catb.org/~esr/faqs/smart-questions.html#idm573)Q: [I'm having problems with my Windows machine. Can you help?](http://www.catb.org/~esr/faqs/smart-questions.html#idm585)Q: [My program doesn't work. I think system facility X is broken.](http://www.catb.org/~esr/faqs/smart-questions.html#idm592)Q: [I'm having problems installing Linux or X. Can you help?](http://www.catb.org/~esr/faqs/smart-questions.html#idm597)Q: [How can I crack root/steal channel-ops privileges/read someone's e-mail?](http://www.catb.org/~esr/faqs/smart-questions.html#idm606)


			[child_database](fa2c4834-45fa-4288-ab99-3cd2494339be)


			## 


			Finally, I'm going to illustrate how to ask questions in a smart way by example; pairs of questions about the same problem, one asked in a stupid way and one in a smart way.


			**Stupid:** Where can I find out stuff about the Foonly Flurbamatic?This question just begs for ["STFW"](http://www.catb.org/~esr/faqs/smart-questions.html#rtfm) as a reply.**Smart:** I used Google to try to find “Foonly Flurbamatic 2600” on the Web, but I got no useful hits. Can I get a pointer to programming information on this device?This one has already STFWed, and sounds like there might be a real problem.


			**Stupid:** I can't get the code from project foo to compile. Why is it broken?The querent assumes that somebody else screwed up. Arrogant git...**Smart:** The code from project foo doesn't compile under Nulix version 6.2. I've read the FAQ, but it doesn't have anything in it about Nulix-related problems. Here's a transcript of my compilation attempt; is it something I did?The querent has specified the environment, read the FAQ, is showing the error, and is not assuming his problems are someone else's fault. This one might be worth some attention.


			**Stupid:** I'm having problems with my motherboard. Can anybody help?J. Random Hacker's response to this is likely to be “Right. Do you need burping and diapering, too?” followed by a punch of the delete key.**Smart:** I tried X, Y, and Z on the S2464 motherboard. When that didn't work, I tried A, B, and C. Note the curious symptom when I tried C. Obviously the florbish is grommicking, but the results aren't what one might expect. What are the usual causes of grommicking on Athlon MP motherboards? Anybody got ideas for more tests I can run to pin down the problem?This person, on the other hand, seems worthy of an answer. He/she has exhibited problem-solving intelligence rather than passively waiting for an answer to drop from on high.


			In the last question, notice the subtle but important difference between demanding “Give me an answer” and “Please help me figure out what additional diagnostics I can run to achieve enlightenment.”


			In fact, the form of that last question is closely based on a real incident that happened in August 2001 on the linux-kernel mailing list (lkml). I (Eric) was the one asking the question that time. I was seeing mysterious lockups on a Tyan S2462 motherboard. The list members supplied the critical information I needed to solve them.


			By asking the question in the way I did, I gave people something to chew on; I made it easy and attractive for them to get involved. I demonstrated respect for my peers' ability and invited them to consult with me as a peer. I also demonstrated respect for the value of their time by telling them the blind alleys I had already run down.


			Afterwards, when I thanked everyone and remarked how well the process had worked, an lkml member observed that he thought it had worked not because I'm a “name” on that list, but because I asked the question in the proper form.


			Hackers are in some ways a very ruthless meritocracy; I'm certain he was right, and that if I _had_ behaved like a sponge I would have been flamed or ignored no matter who I was. His suggestion that I write up the whole incident as instruction to others led directly to the composition of this guide.


			## 


			If you can't get an answer, please don't take it personally that we don't feel we can help you. Sometimes the members of the asked group may simply not know the answer. No response is not the same as being ignored, though admittedly it's hard to spot the difference from outside.


			In general, simply re-posting your question is a bad idea. This will be seen as pointlessly annoying. Have patience: the person with your answer may be in a different time-zone and asleep. Or it may be that your question wasn't well-formed to begin with.


			There are other sources of help you can go to, often sources better adapted to a novice's needs.


			There are many online and local user groups who are enthusiasts about the software, even though they may never have written any software themselves. These groups often form so that people can help each other and help new users.


			There are also plenty of commercial companies you can contract with for help, both large and small. Don't be dismayed at the idea of having to pay for a bit of help! After all, if your car engine blows a head gasket, chances are you would take it to a repair shop and pay to get it fixed. Even if the software didn't cost you anything, you can't expect that support to always come for free.


			For popular software like Linux, there are at least 10,000 users per developer. It's just not possible for one person to handle the support calls from over 10,000 users. Remember that even if you have to pay for support, you are still paying much less than if you had to buy the software as well (and support for closed-source software is usually more expensive and less competent than support for open-source software).


			## 


			_Be gentle._ Problem-related stress can make people seem rude or stupid even when they're not.


			_Reply to a first offender off-line._ There is no need of public humiliation for someone who may have made an honest mistake. A real newbie may not know how to search archives or where the FAQ is stored or posted.


			_If you don't know for sure, say so!_ A wrong but authoritative-sounding answer is worse than none at all. Don't point anyone down a wrong path simply because it's fun to sound like an expert. Be humble and honest; set a good example for both the querent and your peers.


			_If you can't help, don't hinder._ Don't make jokes about procedures that could trash the user's setup — the poor sap might interpret these as instructions.


			_Ask probing questions to elicit more details._ If you're good at this, the querent will learn something — and so might you. Try to turn the bad question into a good one; remember we were all newbies once.


			While muttering RTFM is sometimes justified when replying to someone who is just a lazy slob, a pointer to documentation (even if it's just a suggestion to google for a key phrase) is better.


			_If you're going to answer the question at all, give good value._ Don't suggest kludgy workarounds when somebody is using the wrong tool or approach. Suggest good tools. Reframe the question.


			Answer the actual question! If the querent has been so thorough as to do his or her research and has included in the query that X, Y, Z, A, B, and C have already been tried without good result, it is supremely unhelpful to respond with “Try A or B,” or with a link to something that only says, “Try X, Y, Z, A, B, or C.”.


			_Help your community learn from the question._ When you field a good question, ask yourself “How would the relevant documentation or FAQ have to change so that nobody has to answer this again?” Then send a patch to the document maintainer.


			If you did research to answer the question, _demonstrate your skills rather than writing as though you pulled the answer out of your butt._ Answering one good question is like feeding a hungry person one meal, but teaching them research skills by example is showing them how to grow food for a lifetime.


			## 


			If you need instruction in the basics of how personal computers, Unix, and the Internet work, see [The Unix and Internet Fundamentals HOWTO](http://en.tldp.org/HOWTO/Unix-and-Internet-Fundamentals-HOWTO/).


			When you release software or write patches for software, try to follow the guidelines in the [Software Release Practice HOWTO](http://en.tldp.org/HOWTO/Software-Release-Practice-HOWTO/index.html).


			## 


			Evelyn Mitchell contributed some example stupid questions and inspired the “How To Give A Good Answer” section. Mikhail Ramendik contributed some particularly valuable suggestions for improvements.


	[Introverts](2a39cf4b-4975-430c-b92a-bb89680bb5fb)


		**Psychology Of Introverts** [https://twitter.com/upskillyourlife/status/1497564299010920449?s=28](https://twitter.com/upskillyourlife/status/1497564299010920449?s=28)


	[Parenting](214a9e98-5ca8-4e1e-a7cb-a15d8636497c)


		**This thread is for the white parents, like me. If you have a kid who spends any time online or plays video games, they are being target and recruited to white nationalism.** [https://twitter.com/ted_ra/status/1526184302031020038?s=28&t=6taaVHXWlxZvPmXgI9ouww](https://twitter.com/ted_ra/status/1526184302031020038?s=28&t=6taaVHXWlxZvPmXgI9ouww)


		I'm not a scientist or an academic. I'm a father. And an observer.
		There's nothing that matters more to me than being a parent.
		I want to be great at it. I want to be strong.
		So I study other parents I admire and aspire to emulate.


		## Strong Parents Focus On Themselves


		No, I don't mean they're selfish or self-absorbed at the expense of their kids.


		Quite the opposite.


		Strong parents recognize that the growth and maturity of their kids,


		Will be enabled (or limited) by their own continued growth and maturity.


		## "How Children Raise Parents.”


		Nothing could be more true.


		Parenting continually invites you to grow as a person.


		Strong parents accept that invitation.


		You can't afford to forget -


		Who you are becoming is just as important as who your kids become.


		## Strong Parents Know Their Story


		A mentor once gave me this advice:


		"The greatest gift you can give your children is to heal your childhood."


		Each of us has a complicated relationship with our own childhood.


		And nothing brings it to the surface like parenting.


		## As your kids grow and develop, it takes you back into your story.


		You can try to outrun, ignore, dismiss, overlook, minimize, or deny it.


		But strong parents stand and face it.


		And seek healing.


		You can't fully love your own kids until you come to love the kid inside you.


		## Strong Parents Have Strong Relationships


		Broken relationships are like a tapeworm constantly feeding on your relational capacity.


		They inhibit your ability to give yourself to others, including your children.


		Strong parents recognize this,


		And fight for strong relationships.


		## Strong Parents Think Long Term


		The greatest discovery I've made about parenting is that it's a long game.


		Having the best 4 year old doesn't mean much if they end up bottoming out by 40.


		Thinking long-term about your child's development changes what you do in the short term.


		They weigh their actions and interactions with their kids,


		Carefully considering the long-term impact.


		They accept some short-term losses, headaches, and pain,


		To help their kids win in the long run.


		## Strong Parents Discipline Why Over What


		When my kids were young, I overheard another parent correcting their child.


		What they said caught me by surprise:


		"I care less about what you did,


		And more about why you did it."


		Strong parents are concerned with why rather than what.


		## If you focus solely on behavior, you completely miss the bigger picture.


		You may teach rote obedience and outward compliance,


		But you never shape what matters most -


		The motive behind the action.


		Strong parents want their kids to do the right things for the right reasons.


		## Strong Parents See Their Kids As People


		The strongest parents I know aren't losing sleep about their kid's GPA or future career.


		They have nothing wrapped up in their child's athletic or intellectual ability.


		They see their children as people - not problems or projects.


		## Strong parents treat their kids with dignity and honor their humanity.


		Rather than trying to change who their kids are,


		They smile and express their delight in it.


		They are driven by a profound conviction:


		When you're parenting, you're shaping a life, not a resume.


		## Strong Parents Are Strong People


		Each and every strong parent I've seen is also a strong person.


		They don't shy away from responsibility.


		They're willing to wade into conflict when required.


		They're resilient, disciplined, focused.


		And they offer that strength to others.


	[Selfish](e1dc5480-f61c-49b1-aeea-135cf672e87c)


		The selfish reason to be honest is to clear the mind of exhausting lies and to navigate towards people and situations where you can be completely authentic.


		The selfish reason to love is that it feels better to be in love than to be loved (but don’t expect much back).


		The selfish reason to be ethical is that it attracts the other ethical people in the network.


		The selfish reason to be temperate is that overindulgence desensitizes you to the subtle everyday pleasures of life.


		The selfish reason to be humble is that the more seriously you take yourself, the unhappier you’re going to be.


		The selfish reason to be faithful or dutiful is that it gives you something to care about more than your self.


		The selfish reason to be thrifty is that living far below your means frees you from obsessing over money.


		The selfish reason to be honorable is that self-esteem is just the reputation that you have with yourself. You’ll always know.


		The selfish reason to be calm is that anger burns you first before burning the other.


		A cool and calm person is more effective than an angry and agitated one.


		The selfish reason to forgive is so that you can move on with the rest of your life (but you can’t fake it or rush it).


		The selfish person realizes that happiness belongs to the self-less.


	[Decision making](d1a651ec-2446-4451-8e3b-b7954e3a4a69)


		## The Inside-Outside View


		We have a natural tendency to favour the inside view—our own independent solution to a problem that incorporates all of our hidden biases.


		To make better decisions, we should favour the outside view—one that incorporates the best available data.


		## Ladder of Inference


		Describes the thinking process we go through—often subconsciously—to get from a fact to a decision or action.


		To make better decisions, we should move slowly and deliberately from the bottom of the ladder to the top of the ladder.


		## Confidence Determines Speed vs. Quality


		The more confidence you have in the importance of a problem and your understanding of its solution, the more you should focus on quality.


		However, if you need to learn more, move fast and break things.


		## Devil’s Advocate Position


		The antidote to confirmation bias.
		
		It involves forcing yourself to view a decision from the opposite viewpoint or finding people who disagree with you.
		
		It forces you to create a more compelling argument.


		## Pre-Mortem


		Involves assuming that your decision has failed and working backwards to determine what the potential causes were.


		This process has multiple benefits:
		• Removes overconfidence and irrational optimism
		• Reveals blind spots
		• Simplifies thinking


		## Post-Mortem


		Regardless of success or failure, this can be used to drive continuous improvement in your decision-making.


		Here, you ask:
		• What went well?
		• What went poorly?
		• What can be improved next time?


		With the answers, future decisions will be better informed.


		## Trees


		These are tree-like graphs with the branches showing results of possible choices for a given decision or action.


		The decision tree allows options to be compared against each other, for both risk and return.


		They're particularly helpful for financial decisions.


		## Information Overload


		Information overload is when you have too much information at hand.


		This causes decisions to take too long.


		It also leads to 'analysis paralysis' where your decision-making suffers paralysis because you over-analyze the body of information available.


		## Analysis Paralysis


		It's the paradox of choice: having too many good options slows us down because the best one isn't clear.


		Remember: by not making a choice, you are actually making a choice: the status quo.


		A model to cope with this: reversible vs. irreversible decisions.


		## Reversible vs. Irreversible Decisions


		Irreversible decisions are 'one-way doors.'


		They must be made slowly and deliberately.


		Reversible decisions are 'two-way doors.'


		These decisions can and should be made quickly.


		## Luck Razor


		If stuck with 2 equal options, pick the one that feels like it will produce the most luck later down the line.


		Should I stay in tonight or should I go and meet this interesting stranger?


		Choose to increase your surface area of luck when you have the choice.


		## Make Proud Decisions for Your 80-Year Old and 10-Year Old Self


		Your 80-year-old self helps you makes decisions you won't regret when you're old.


		Your 10-year-old self reminds you to stay foolish and have some fun along the way.


		## 10/10/10 Rule


		We're all guilty of making decisions without thinking about long term consequences.


		To avoid this, ask:
		• How will I feel about this 10 minutes from now?
		• 10 months from now?
		• 10 years from now?


		This helps clarify the decision that results in a win/win/win.


	[Politics](838630db-2a97-4dbd-a473-4cd5a53d41a6)


		![](https://s3.us-west-2.amazonaws.com/secure.notion-static.com/629cbf23-0dab-47da-bed5-be6b620cca4b/FRx923HWUAEO4Gl.jpeg?X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Content-Sha256=UNSIGNED-PAYLOAD&X-Amz-Credential=AKIAT73L2G45EIPT3X45%2F20220725%2Fus-west-2%2Fs3%2Faws4_request&X-Amz-Date=20220725T091440Z&X-Amz-Expires=3600&X-Amz-Signature=c08f065174a214064430824e50d9252984437899ac720b2d98e791bbea3f9884&X-Amz-SignedHeaders=host&x-id=GetObject)


	### Inclusion


	[https://github.com/ryanburgess/inclusion](https://github.com/ryanburgess/inclusion)


	### Life


	[https://www.reddit.com/r/AskReddit/comments/ghmr3e/people_who_are_40_and_happy_with_their_life_what/?utm_source=share&utm_medium=ios_app&utm_name=iossmf](https://www.reddit.com/r/AskReddit/comments/ghmr3e/people_who_are_40_and_happy_with_their_life_what/?utm_source=share&utm_medium=ios_app&utm_name=iossmf)


	**Honesty** [https://debliu.substack.com/p/the-importance-of-being-plainspoken](https://debliu.substack.com/p/the-importance-of-being-plainspoken)


	**Carrer** [https://mjambon.com/2015-01-03-universal-career-advice](https://mjambon.com/2015-01-03-universal-career-advice/)


	[https://neurodiversity.wiki](https://neurodiversity.wiki/)


[Remote](93ac64ee-45d9-45d2-9f28-a65bfc7b7bd1)


	**Awesome digital nomads** [https://github.com/cbovis/awesome-digital-nomads](https://github.com/cbovis/awesome-digital-nomads)


	[What Most Remote Companies Don’t Tell You About Remote Work](https://doist.com/blog/mental-health-and-remote-work/)


	Onboarding: https://twitter.com/rothgar/status/1296911972215058432?s=21


	[https://klinger.io/post/180989912140/managing-remote-teams-a-crash-course](https://klinger.io/post/180989912140/managing-remote-teams-a-crash-course)


	[Handbooks](9b05f6d4-38e7-4cc7-862b-f46d35288fda)


		[Remote.com](http://remote.com) [https://www.notion.so/remotecom/Handbook-a3439c6ccaac4d5f8c7515c357345c11](https://www.notion.so/remotecom/Handbook-a3439c6ccaac4d5f8c7515c357345c11)


		Zapier [https://zapier.com/learn/remote-work](https://zapier.com/learn/remote-work/)


		GitLab [https://about.gitlab.com/handbook](https://about.gitlab.com/handbook/)


		Toptal [https://www.toptal.com/remote-work-playbook](https://www.toptal.com/remote-work-playbook)


		Enzyme Corp [https://enzymecorp.github.io/handbook/](https://enzymecorp.github.io/handbook/)


	[Nomad](57bebbc4-d3e0-4825-9f55-d5a26ee89d63)

		- [Going nomad](https://krausefx.com/blog/going-nomad)
		- [Building an Open-Source Publishing Platform That Makes \$63,000/mo with John O'Nolan of Ghost Podcast](https://www.indiehackers.com/podcast/007-john-onolan-of-ghost)
		- [Nomad List](https://nomadlist.com/)
		- [One year nomad - a review (2018)](https://krausefx.com/blog/one-year-nomad)
		- [Hundred Rabbits](https://100r.co/) - [Devine](http://xxiivv.com/) & [Rekka](http://kokorobot.ca/), part of a traveling design studio on sailboat. Very [inspiring](https://www.youtube.com/channel/UCzdg4pZb-viC3EdA1zxRl4A).
		- [Seats2meet](https://www.seats2meet.com/) - Work together, find relevant people, events and locations.
		- [Ask HN: How are Digital Nomads coping with travel restrictions? (2020)](https://news.ycombinator.com/item?id=24867241)
		- [Ask HN: Digital nomads, where's the best place in the world to work from? (2021)](https://news.ycombinator.com/item?id=27129943)
		- [Most Liked Places with Many Nomads for Families to Live](https://nomadlist.com/most-liked-places-with-many-nomads-for-families-to-live)
		- [Where would be an awesome place to work remotely (with a family) for a month? (2021)](https://twitter.com/Austen/status/1419332623420198919)
		- [Ask HN: Where can I live off 1k USD per month? (2021)](https://news.ycombinator.com/item?id=28309520)
		- [Nomad Capitalist - YouTube](https://www.youtube.com/c/nomadcapitalist/videos)
		- [Nomad Capitalist Book](https://nomadcapitalist.com/book/)
		- [Robert Kiyosaki’s Thoughts on Entrepreneurship (2022)](https://www.youtube.com/watch?v=u4UtdCuvCz4)
		- [What do you wish you knew about digital nomads when you started?](https://www.reddit.com/r/digitalnomad/comments/u905el/what_do_you_wish_you_knew_when_you_started/)
		- [Share the biggest problem you face living as a digital nomad (2022)](https://www.reddit.com/r/digitalnomad/comments/uba7pn/share_the_biggest_problem_you_face_living_as_a/)
		- [Awesome Digital Nomads](https://github.com/cbovis/awesome-digital-nomads)

[Startups](a93d9ec7-db3e-49e9-891e-18e9dc65bed7)


	The most complete list of open startups [https://openstartup.tm](https://openstartup.tm/)


	Search for communities: [https://thehiveindex.com](https://thehiveindex.com/)


	[MVP of pilars](32ede643-334b-408f-9e3f-6633fe526412)


		Mission: Why


		Vision: What


		Strategy: How


		Segmentation: Who


		Positioning: Where


		Roadmap: When


	[Feels faster vs makes u faster](9c7ceced-2374-45af-8c52-7309e9fefb75)


		![](https://s3.us-west-2.amazonaws.com/secure.notion-static.com/8365292c-89a7-429d-94a7-724fa8d99cea/DkpuUnVUUAEKJpJ.jpeg?X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Content-Sha256=UNSIGNED-PAYLOAD&X-Amz-Credential=AKIAT73L2G45EIPT3X45%2F20220725%2Fus-west-2%2Fs3%2Faws4_request&X-Amz-Date=20220725T091443Z&X-Amz-Expires=3600&X-Amz-Signature=fe1ea71473a5f5da4f213c14f31eaf9a317d9a51e8d2e1149193b5ac22102aea&X-Amz-SignedHeaders=host&x-id=GetObject)


	[KPIs to keep track](e4493a78-f6ea-4d23-9e3f-14e5b63fc12d)


		## Revenue Split


		Split this between Recurring and Non-Recurring.


		Recurring revenue is perceived as more valuable than Non-Recurring Revenue due to its predictability and stickiness.


		The higher the % of recurring revenue, the higher the valuation multiple.


		## Gross Margin (GM)


		Revenue - Cost Of Goods Sold / Revenue


		GM tells you how much revenue you get to keep after paying for the production of your product or service.


		The higher the GM, the more efficient your production (better processes, cheaper supply etc).


		## Net Profit Margin (NPM)


		Net Income / Revenue


		This indicates how much revenue is left after ALL costs and expenses have been paid.


		The higher the NPM, the more profitable your business.


		## Lifetime Value (LTV)


		Revenue Since Inception / # of Customers


		LTV measures how much each customer contributes to your business.


		LTV is driven by (1) profitability per transaction and (2) number of transactions per customer.


		Increase both to increase LTV.


		## Cost of Customer Acquisition (CAC)


		Marketing Costs + Sales Costs / # of Customers Acquired


		Usually compared against LTV to determine if how much it costs to acquire a customer is worth the value expected from said customer.


		Ideally you should have an LTV:CAC > 3.


		## Days Sales Outstanding (DSO)


		Account Receivables / Sales x 365 days


		Measures how quickly your customer pays their bills.


		If DSO is meaningfully higher than credit terms (days), you have a collections issue.


		## Days Payable Outstanding (DPO)


		Account Payables / COGS x 365 days


		Measures how quickly you pay your bills.


		Increases could signal cashflow constraints within your business.


		Ideally,  DSO < DPO.


		This means you are getting paid BEFORE paying your suppliers.


		## Cash Burn Rate


		Company cash / Monthly expenses


		Measures how quickly you are burning through your cash reserves.


		Especially important in the early stages of a business or when there is a significant disruption in the market (e.g. COVID, recession etc).


		## Current Ratio


		Current assets / Current liabilities


		Measures whether you have the ability to meet your short-term obligations (e.g. pay your suppliers).


		If Current ratio is below 1, it could be a sign that your business is in financial difficulty.


		## Gross Revenue Churn


		Revenue Lost for the period / Total Revenue at the start of period


		Measures percentage of revenue lost during a period.


		Significant increases are early warning signals of problems (e.g. customer distress, increasing competition etc).


	[Agendas](5f70e771-fb7e-4831-b60a-df8c5d621d57)


		[https://www.hugo.team/meeting-templates](https://www.hugo.team/meeting-templates)


[Food](66e4ee59-94f1-4b08-a3ad-ebaf1fb1815e)


	How to create a diet


	Added sugar


	Fat


	**Obesity** [https://slimemoldtimemold.com/2021/07/07/a-chemical-hunger-part-i-mysteries](https://slimemoldtimemold.com/2021/07/07/a-chemical-hunger-part-i-mysteries/)


	**Super alimentos**

	- Brocoli
	- Kale
	- Patata
	- Sweet potato
	- Manzana
	- Hummus (garbanzos)

[Sport](6ebc6c7b-c092-4a68-8e7c-cba50a5bc9cd)


	[Triathlon](d277a068-69cd-47f9-b500-a6225af13405)


		[Half ironman plan](21d545ca-c380-4958-89e5-bdfad154fdaf)


			[https://elultimotriatleta.com/wp-content/uploads/suscriptores/triatlon/plan_entrenamiento_medio_ironman.pdf](https://elultimotriatleta.com/wp-content/uploads/suscriptores/triatlon/plan_entrenamiento_medio_ironman.pdf)


			[https://www.sportssantander.es/Triatlon/entrenamientos/half-intermedio](https://www.sportssantander.es/Triatlon/entrenamientos/half-intermedio)


		[https://juanmariajimenez.com/planes-de-entrenamiento/](https://juanmariajimenez.com/planes-de-entrenamiento/)


		## Jordi’s Ideal week


		M: easy run+strength


		T: bike+easy run


		W: strength+hard run


		T: hard buke+strength


		F: tempo run


		S: long and hilly bike


		S: long run + strength


	[Running](8f210383-6a04-469b-a895-c5890ad1732d)


		Plan de entreno de maratón [https://www.trainingpeaks.com/training-plans/running/marathon/tp-180544/marathon-2h30-3h](https://www.trainingpeaks.com/training-plans/running/marathon/tp-180544/marathon-2h30-3h)


		[10k training](60b917ce-d05a-4e33-979b-c45a6b1154d4)


			![](https://s3.us-west-2.amazonaws.com/secure.notion-static.com/244a3211-d395-4e4d-8259-efab5d83008b/D1D83EA2-076B-4305-8A83-204C045CE164.webp?X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Content-Sha256=UNSIGNED-PAYLOAD&X-Amz-Credential=AKIAT73L2G45EIPT3X45%2F20220725%2Fus-west-2%2Fs3%2Faws4_request&X-Amz-Date=20220725T091447Z&X-Amz-Expires=3600&X-Amz-Signature=657fd138d9269037ec763183d0fcc3e7f622ca436151064fe3a892c042540f26&X-Amz-SignedHeaders=host&x-id=GetObject)


	[Strength](4511cdde-aa30-4e32-89d6-5f0afe196aaf)


		[child_database](de160d87-3892-4731-b5a8-d7fce03620be)


	[Suplements](ba0726dc-9383-4826-83f9-ef2cfa519961)


		[https://examine.com/supplements/creatine/#effect-matrix](https://examine.com/supplements/creatine/#effect-matrix)


[Money](f3c59195-9e44-4ba6-bdab-c25e80b27f2f)


	**Equity**


	[https://blog.pragmaticengineer.com/equity-for-software-engineers](https://blog.pragmaticengineer.com/equity-for-software-engineers/)


	[https://github.com/jlevy/og-equity-compensation](https://github.com/jlevy/og-equity-compensation)


	**The Psychology of Money** [https://www.collaborativefund.com/blog/the-psychology-of-money](https://www.collaborativefund.com/blog/the-psychology-of-money/)


	[ETF](29fb81e1-5eb5-4eee-9dde-4fbf3d6c0028)


		[https://decryptom.notion.site/Free-ETF-Portfolio-Examples-117f973a455f43adb76ab6383b55fbc6](https://decryptom.notion.site/Free-ETF-Portfolio-Examples-117f973a455f43adb76ab6383b55fbc6)


	[Crypto](3ff19585-42f8-40c9-9287-07b08ea0bfe9)


		[https://thecoinperspective.com](https://thecoinperspective.com/?c=XRP)


		[https://www.marketcapof.com](https://www.marketcapof.com/)


		### Ethereum


		[https://ethereum.org](https://ethereum.org/en/)


		[https://github.com/ethereumbook/ethereumbook](https://github.com/ethereumbook/ethereumbook)


		### Tezos


		[https://tezos.com](https://tezos.com/)


		### Stable coins


		[https://tether.to/en](https://tether.to/en/)


		[https://www.terra.money](https://www.terra.money/)


		### Guides


		[https://therevealer.hashnode.dev/how-cryptocurrency-actually-work-everything-you-need-to-know](https://therevealer.hashnode.dev/how-cryptocurrency-actually-work-everything-you-need-to-know)


		[https://web3.hashnode.com/how-data-is-processed-and-stored-in-the-blockchain](https://web3.hashnode.com/how-data-is-processed-and-stored-in-the-blockchain)


[Product](436b7b5e-02ab-4c2a-a347-0f7eec23b24e)


	### Beware, not every itch is worth scratching…


	🔷Not every opportunity is worth taking


	🔷Not every dangled carrot is worth chasing


	🔷(You might be caught in a rat race)


	### To break free, recognize you’re in a race…


	🔷Consider your obligations


	🔷Imagine an alternative universe


	🔷And ask yourself, “Why not?”


	### It’s hard, but it doesn’t take much (and almost anyone can do it)…


	🔷140 views at 5 percent conversion = seven sales


	🔷Seven sales a day of a $39 product = $275 per day


	🔷Seven sales a day of a $39 product = $100,000 per year


	### Start with the hardest part…


	🔷Be willing to jump off the wrong train


	🔷Be willing to write off past ambitions


	🔷Be willing to detach your identity from your accomplishments


	🔷Otherwise you might get stuck enduring an existence full of wrong stops


	### Take stock of your means…


	🔷Time


	🔷Skills


	🔷Location


	🔷Interests


	🔷Strengths


	🔷Resources


	🔷Experience


	🔷Perspective


	🔷Connections


	🔷Cash at hand


	### Curb your ambitions…


	🔷Keep reducing scope


	🔷Keep moving the finish line closer


	🔷Keep giving yourself free energy


	🔷Keep the complexity of what you do within your means


	### Figure out what you don’t like…


	🔷Procrastinate on purpose to find what demotivates you


	🔷(What you’re putting off is what you don’t like)


	🔷Learn from your internal resistance to find your true preferences


	### Slowly evolve your lifestyle to better match your true preferences…


	🔷Do things for their own sake


	🔷Do what no one’s forcing you to do


	🔷Do what you’re intrinsically motivated to do


	🔷Gradually do fewer things you’d rather not do


	🔷(Only intrinsic motivation lasts)


	### Set a direction instead of a goal…


	🔷You can’t predict what will work


	🔷You can’t predict what will last


	🔷You won’t know if a great idea is really great until it survives impact with reality


	🔷(Goals tend to get in the way of letting you do what you should be doing)


	### You don’t need a big vision to succeed…


	🔷There’s no need to change the world


	🔷There’s no need to conquer the competition


	🔷There’s no need to dominate the market


	🔷There’s no need to disrupt anything


	🔷Just throw yourself into random tasks until inspiration meets opportunity


	### Make time your friend…


	🔷Cut costs


	🔷Make do with less


	🔷Reconsider your needs


	🔷Don’t spend more than you earn


	🔷Make your worst-case scenario a slow success


	### Work hard to earn credibility…


	🔷Do something interesting in real life


	🔷Prove yourself by making something interesting


	🔷Without credibility, nobody will listen to what you have to say


	### Avoid low probability bets…


	🔷Stack odds in your favor


	🔷Choose your projects carefully


	🔷Study your opportunities carefully


	🔷Business is a conjecture that an idea will work out


	🔷Don’t ignore uncertainty in a randomness-laden venture


	### Make many small bets (and keep them small)…


	🔷Don’t be greedy


	🔷Control the amount wagered


	🔷Go for the low hanging fruit first


	🔷Keep investments tiny and bounded


	🔷Try many things in parallel or almost in parallel


	🔷You’ll learn more this way than any other way


	### Build something imperfect that works…


	🔷Start with a very small product


	🔷Pick something you can finish in two weeks


	🔷Charge ten dollars for it


	🔷(Perfectionism is fine, as long as you realize you're doing it only for your own amusement)


	### Don’t optimize or polish your products…


	🔷Focus on substance, not optimizations


	🔷Let the scrappiness be part of the charm


	🔷The returns on polishing and optimizing are small


	🔷A book can be your life's work, presented as a masterpiece, or it can be a scrappy brain dump


	### Keep idle time in your system…


	🔷Idle time is slack


	🔷Slack lets you immediately explore and pounce on opportunities


	🔷By not optimizing to the limit, you can deal with randomness without breaking down


	### Remember, growth is not linear…


	🔷Progress comes from random, high impact lucky events


	🔷Realize a fraction of the effort gets most of the results


	🔷Recognize which fraction to focus on


	🔷Use the time you bought back to do whatever you want


	### Do a lot when inspiration strikes…


	🔷Take long breaks in between


	🔷Most things require intensity over consistency


	🔷Consistency works, but it's unpleasant


	🔷What can be done with consistency is often more enjoyable when done with intensity (otherwise you're fighting yourself)


	### If there’s no one around, go where people already hang out…


	🔷Make yourself useful


	🔷Share what you’ve done


	🔷Share what you’re learning


	🔷Let yourself be opinionated


	🔷Share how your product is doing


	🔷Teach what you know (it took a lifetime to acquire!)


	### When you promote yourself…


	🔷You promote your product


	🔷You have automatic authority


	🔷You find people who want to learn from you specifically


	🔷You create an uncontested market space (competition becomes irrelevant because nobody can copy you)


	### Strive to be an artisan…


	🔷Be creative


	🔷Don’t follow others


	🔷Make your work a business


	🔷Don’t cut corners for efficiency


	🔷Say no to things you’d rather not do


	🔷Do the best work you can, for its own sake


	🔷Never sell something you know is defective


	### A good life is a story you're proud of… Pride comes from the story we tell ourselves about how we created something in the circumstances we were in.


[Marketing](a51fec8e-3645-4fbf-adfc-d2b1fd607820)


	[LisaDziuba/Marketing-for-Engineers: A curated collection of marketing articles & tools to grow your product.](https://github.com/LisaDziuba/Marketing-for-Engineers)


	[https://justinjackson.ca/build](https://justinjackson.ca/build)


	[https://marketingexamples.com](https://marketingexamples.com/)


	[Copy](916ab9a4-dccc-4fd2-b121-1ede7b280c6b)


		[Landing page](5dd95197-944d-471d-ae0d-05b6b5d401dd)


			### Do your research first


			Research is very important. I can't stress this enough. You already know your target audience. Now, dig deeper. Find out what they like and don't like about your competitors. Notice how they speak on forums, social media, and the keywords they use in reviews.


			Why is research so important? You are writing for your ideal customer, not for yourself. What you believe in doesn't matter. Your opinions don't matter. You don't know what's best, your ideal customers do even though you may fit the buyer persona.


			You need to put yourself in your prospects' shoes and see things from their perspective.


			### Focus on one big idea - your USP


			Highlight your USP first then build on it with the benefits and features of your product/service.


			We find it easier to focus on one thing at a time. Your readers will find it easier to differentiate you from competitors with one thing. So highlight your USP in the main title and optional subtitle, then use the headings, subheadings, and body to build on it.


			You can be creative with the wording but use a voice your ideal customer can relate to.


			Here's an example:


			_main title: "Unlimited movies, TV shows, and more."_


			_subtitle: "Watch anywhere. Cancel anytime."_


			_heading #1: "Enjoy on your TV."_


			_heading #2: "Download your shows to watch offline."_


			_heading #3: "Watch everywhere."_


			### Write like how your ideal customers speak


			Use the language your prospects use in terms of slang and technical jargon. Use the keywords they use they talk about their pain points and the perfect solution to their problem. Match their tone as well.


			This makes you sound like someone who can relate to them and understand their problems.


			Use "you"


			Your website is like your salesperson working 24/7. So write as if you're speaking to one person.


			Every visitor has a one-on-one interaction with your website. Using "you" will let them know that you're directly speaking to them, like how I'm directly speaking to you.


			As the saying goes: _if you're speaking to everyone, you're speaking to no one._


			### Add social proof or an alternative


			If you have testimonials, reviews, client lists, places you've been featured in, add them. It builds credibility instantly.


			If you don't, find another way to build authority. It could be your values, your process, your background, your team's background. You can also add badges or even make a promise.


			Earn. Their. Trust.


			### Be clear and concise


			Get straight to the point. Don't waste your reader's time beating around the bush.


			For example, instead of this:


			_"Our team has already been recognized by market leaders and we are setting the trend for industry standards."_


			Use this:


			_"Our team is recognized by market leaders as industry trendsetters."_


			### ONE compelling call to action


			Stick with ONE call to action. The more CTAs, the lower the conversion rates. This is because of decision fatigue (the weary feeling you get after being faced with too many decisions).


			If you have to use more than one, use different colors and text sizes to contrast between them. You may also make one look more compelling than the other.


			You can repeat this call to action throughout your landing page. But make it easier for them to choose by sticking with a uniform text. More variations will give your prospect decision fatigue


		[Tips for wording](51a22edf-62de-4bb0-b2c1-01af112210b8)


			## **1) Write with your eraser**


			You get 100 bucks for every word you rub out from your title:


			![](https://s3.amazonaws.com/harrydry/gdmarketing/ctt1.png)


			## **2) Don't exaggerate**


			An honest line always feels warmer:


			![](https://s3.amazonaws.com/harrydry/gdmarketing/ctt2.jpg)


			## **3) No one cares what you can do**


			Everyone cares what you can do _for them_.


			![](https://s3.amazonaws.com/harrydry/gdmarketing/ctt3.jpg)


			## **4) Avoid the passive voice**


			It's indirect and awkward:


			![](https://s3.amazonaws.com/harrydry/gdmarketing/ctt4.png)


			## **5) Don't kill your personality**


			The best brands feel “real”:


			![](https://s3.amazonaws.com/harrydry/gdmarketing/ctt11a.png)


			## **6) Avoid “landing page words”**


			_Unlock_, _unleash_, _enhance_, _exceed_, _empower_, _supercharge_, etc.


			Real people don't use them.


			![](https://s3.amazonaws.com/harrydry/gdmarketing/ctt13.png)


			## **7) Find the tension**


			“Pleasant” gets forgotten. Conflict creates interest:


			![](https://s3.amazonaws.com/harrydry/gdmarketing/ctt12d.png)


			## **8) Write how you talk**


			Casual. Colloquial. Full of pronouns:


			![](https://s3.amazonaws.com/harrydry/gdmarketing/ctt5.png)


			## **9) Avoid “contained” titles**


			Write something that pulls your reader down your page:


			![](https://s3.amazonaws.com/harrydry/gdmarketing/ctt14.png)


			## **10) Write scannable copy**


			Formatting matters:


			![](https://s3.amazonaws.com/harrydry/gdmarketing/ctt6.png)


			## **11) Stories make you memorable**


			I couldn't list The Ten Commandments. I could tell you what happened to Adam and Eve:


			![](https://s3.amazonaws.com/harrydry/gdmarketing/ctt8.png)


			## **12) More periods, fewer commas.**


			Periods mean short sentences. We like short sentences.


			Commas mean long, painful sentences, like this one, which _New Yorker_ writers think are clever, but real people find torturous, because they wind on and on without actually saying anything.


			h/t [David Perell](https://twitter.com/david_perell/status/1250149037837176834)


			## **13) Kill adverbs. Kill adjectives.**


			They're flowery. They're vague. They try too hard:


			![](https://s3.amazonaws.com/harrydry/gdmarketing/ctt9.png)


			## **14) Think slippery slide**


			Every line of copy should lead to the next.


			Watch this ad. You won't be able to stop:


			## **15) Fence sitters don't buy**


			Go to the edge:


			![](https://s3.amazonaws.com/harrydry/gdmarketing/ctt7.png)


			## **16) Your first line is crucial**


			If people don’t read it, they’re not going to read your second line either.


			Keep it short:


			![](https://s3.amazonaws.com/harrydry/gdmarketing/ctt10.png)


			## **17) Copywriting is selling**


			Don’t romanticize it. The goal isn't to be clever or cute.


			The goal is to inspire action:


			![](https://s3.amazonaws.com/harrydry/gdmarketing/ctt16.png)


			## **You made it!**


	[SEO](57d33b68-424b-4732-bc54-c6bea463f834)


		[Tools](3894ecfd-7700-41a3-bf57-ad1ca069aacf)


			[Open Site Explorer](http://www.opensiteexplorer.org/)


			[Page Analyzer. Keyword placement, keyword density, prominence , link popularity, google positions and much more.](http://www.ranks.nl/tools/spider.html)


			[Ahrefs Site Explorer & Backlink Checker](https://es.ahrefs.com/)


			[Keyword Rank Checker & SERP Checker. Keyword Rankings in Google, Yahoo & Bing](https://serps.com/tools/rank_checker)


			[Website Review and free SEO audit tool - Seoptimer](http://www.seoptimer.com/)


			[Anchor Text Over Optimization Tool and Anchor Text Diversity Report by Remove'em](http://www.removeem.com/ratios.php)


			[Your New SEO Browser: Browseo](http://www.browseo.net/)


			[Keyword Tool: 750 Google Keyword Suggestions for Free. Use 192 Google Domains & 83 Languages](http://keywordtool.io/)


			[Keyword suggestion tool — Google suggest scraper — Übersuggest](http://ubersuggest.org/)


			[Free keyword suggestion tool for SEO, Adwords & blogging from Wordtracker - the leading keyword research tool](https://freekeywords.wordtracker.com/)


			[Free Keyword Density Analyzer Tool](http://tools.seobook.com/general/keyword-density/)


			[Keyword Density Checker Tool - iWEBTOOL.com](http://www.iwebtool.com/keyword_density)


			[Majestic SEO : Backlink Checker & Site Explorer](http://www.majesticseo.com/)


			[The W3C Markup Validation Service](http://validator.w3.org/)


			[OpenLinkProfiler.org - The freshest backlinks. For free.](http://www.openlinkprofiler.org/)


			[woorank](http://www.woorank.com/es/www/)


			[Emkei's Instant Mailer](http://emkei.cz/)


		[Articles](cff94c62-c0de-4fd7-9420-677a8283b02a)


			[Trucos Google Analytics - Análisis Web, SEO y Social Media](http://trucosgoogleanalytics.com/)


			[Think Bigger: 28 Ways to Be a Better SEO](http://seogadget.com/think-bigger-be-a-better-seo/?utm_content=buffer6b806&utm_source=buffer&utm_medium=twitter&utm_campaign=Buffer)


			[.htaccess made easy | configure, optimize & secure your website](http://htaccessbook.com/)


			[Learning_SEO_from_the_Experts.pdf](http://cdn1.hubspot.com/hub/53/Learning_SEO_from_the_Experts.pdf)


			[Google Webmasters - YouTube](http://www.youtube.com/user/GoogleWebmasterHelp)


			[Learn SEO | SEO Hacker School](http://seo-hacker.org/)


			[Watch the Online Video Course SEO Fundamentals](http://www.lynda.com/Google-Analytics-tutorials/SEO-Fundamentals/89810-2.html)


			[Free Ebook: Learning SEO from the Experts](http://offers.hubspot.com/learning-seo-from-the-experts)


			[Learn SEO - Free SEO Tips](http://www.seobook.com/learn-seo/)


			[A Web Designer's SEO Checklist (Including Portable Formats) – Development – Tuts+ Tutorials](http://dev.tutsplus.com/articles/seo-checklist--webdesign-10740)


			[Black Hat Forum Black Hat SEO](http://www.blackhatworld.com/blackhat-seo/)


			[Marketing de Contenidos | 40deFiebre | Blog de Socialmood |](http://www.40defiebre.com/)


			[Growth Hacking Labs - Cómo convertirte en Growth Hacker](http://growthhackinglabs.com/)


			[Natzir Turrado · Conversión, Analítica Web y SEO](http://www.analistaseo.es/)


			[Últimos artículos de Monetizados.com](http://www.monetizados.com/blog)


			[RiteTag logo](https://ritetag.com/audit)


			[Blog - Javier Gosende](http://www.javiergosende.com/blog)


			[Blogger 3.0 de Dean Romero](http://blogger3cero.com/)


			[SEO Blog](http://seoblog.es/)


			[seo-hacker.org](http://seo-hacker.org/)


			[Eduard Maeso](http://eduard.maeso.me/blog/)


			[Guía SEO](http://javiercasares.com/seo/)


			[SEO](http://www.seochat.com/)


			[Matt Cutts: Gadgets, Google, and SEO](http://www.mattcutts.com/blog/)


			[SEO ™ ★★★★☆ SEO y posicionamiento en Google | Blog SEO | Posicionamiento en Buscadores](http://www.mecagoenlos.com/)


			[We Can Buy Google, el Bloog](http://www.wecanbuygoogle.com/blog/)


	[Brand strategy](7b06defc-bf05-4e77-8073-0079593c75a9)


		How to build a brand strategy from 0-1: a beginning guide
		
		Reminder: brand strategy should be done WITH your head of product vs presented to them.
		
		This creates buy-in and alignment on why this is important.
		Brand strategy is NOT a marketing plan.
		Brand strategy is WHY you will win.
		
		Marketing plan is HOW: levers you will pull to hit your goals.
		
		Step 1: review competitive landscape 


			Do tear downs.


			Understand leading value props.


			Interview users of your competition to understand what’s working, what’s not.


			Know who the players are and where they play vs where you will play.


		Step 1b: create your “Only” statement


			Complete this sentence: "We are the only brand that does x, y and/ or z."


			What makes you different and how would you say that efficiently.


		Step 2: identity customer segments


			Data helps here. If you already have a product, know who is already a purchaser and why.


			Otherwise, create user personas of ideal customers.Have fun! How do they get news? What social accounts do they follow? What shows are they watching?


		Step 3: use 1 & 2 to create your brand pyramid


			A brand pyramid helps you to think about the core essence / brand sentiment. 
			How do you want to make someone feel.


		Step 4: bring that feeling to life


			**TONE**


			Create your voice & tone of your brand. Use statements like: We are this, not this.
			Ex: we are bold, not judgemental
			Ex: we are funny, not crass
			
			Pull together examples of social captions, welcome email and product copy for North Star.


		Step 5: bring that feeling to life


			**VISUAL**


			Pull inspirational photos to guide a designer to create 3 mood boards for tour brand to react to.
			
			Use the brand pyramid to guide you.
			Refine and get to your MVP quickly. Don’t obsess over every pixel in the beginning.


		Step 6: Learn and Iterate


			A brand is a living thing. Just like a human it learns and grows as new pieces of information from customers, product and market.


	[Marketing 101](746a34c7-26f9-480b-a508-b96d8c8061ee)


		Marketing 101: a startup guide to building your first marketing calendar
		[https://twitter.com/AmandaMGoetz/status/1303373356415279105](https://twitter.com/AmandaMGoetz/status/1303373356415279105)


		
		Marketing 101: Influencer marketing on a limited budget


		[https://twitter.com/AmandaMGoetz/status/1310987368787304449](https://twitter.com/AmandaMGoetz/status/1310987368787304449)


		Marketing 101: Content strategy in the early days
		- where to focus
		- how to measure
		- resourcing, etc


		[https://twitter.com/AmandaMGoetz/status/1305909984711135232](https://twitter.com/AmandaMGoetz/status/1305909984711135232)


		Marketing 101: Building community
		How do brands build a loyal base?
		Which comes first, audience or product?
		Niche or broad? Which is better?


		[https://twitter.com/AmandaMGoetz/status/1337038773910196224](https://twitter.com/AmandaMGoetz/status/1337038773910196224)


		Marketing 101: What does Product / Market fit mean in the early days of a startup?


		[https://twitter.com/AmandaMGoetz/status/1313515667568631808](https://twitter.com/AmandaMGoetz/status/1313515667568631808)


		Marketing 101: building a personal brand
		- what does personal brand mean
		- why should you care
		- how to distinguish it against the company you work for
		- how to do it w/ support from your boss
		- how to build yours


		[https://twitter.com/AmandaMGoetz/status/1322196096953831425](https://twitter.com/AmandaMGoetz/status/1322196096953831425)


	[Product Hunt Launch Checklist](c2277d36-696f-475f-98b9-56023c6d1a21)


		# 0. Get startedìn


		---


		[Resources](cafe6771-ce24-40b6-87ee-dc81c4bc26b5)


			[bookmark](https://www.buildingstartups.co/blog/how-to-launch-on-producthunt-successfully-strategic-top-3-guarantee)


			[bookmark](https://typestudio.co/blog/product-hunt-learnings/)


			[bookmark](https://taskablehq.com/templates/checklist-launching-product-hunt)


			[bookmark](https://blog.producthunt.com/how-to-launch-on-product-hunt-7c1843e06399)


			[bookmark](https://producthunt.taskablehq.com/)


			[bookmark](https://pierretillement.com/Launch-on-PH-c0ce11d231bb4c00a3f415646415fb5c)


			[bookmark](https://medium.com/startup-grind/how-we-got-1000-upvotes-on-product-hunt-by-curating-a-checklist-from-50-successful-launches-6b77ce29b444)


			[bookmark](https://twitter.com/IndieHackers/status/1325702258831613952)


			[bookmark](https://www.indiehackers.com/post/1-most-commented-on-product-of-the-week-on-product-hunt-7e753b13f7)


			[bookmark](https://mention.com/en/blog/hack-product-hunt-launch/https://mention.com/en/blog/hack-product-hunt-launch/](https://mention.com/en/blog/hack-product-hunt-launch/))


			[bookmark](https://help.producthunt.com/en/articles/2731371-how-to-add-a-product-hunt-badge-to-your-website)


			[bookmark](https://www.demandcurve.com/playbooks/product-hunt#ejc1nkzigipixxs9xsd5qs)


			[embed](https://twitter.com/IndieHackers/status/1325702235913859073?s=20)


			[bookmark](https://growthhunt.co/ce6639d433814ee191cc519aa416dccf)


		# 1. Build an audience


		---

		- [ ] Look for similar products on PH and reach out to the people who upvoted or commented
		- [ ] Join relevant slack groups or communities and contribute
		- [ ] Use Tweetdeck to scan conversations on Twitter about similar products
		- [ ] Reply to relevant questions on forums (Reddit, Quora, Indie Hackers...)
		- [ ] Share your MVP or product with [established makers](https://makernetwork.app/500makers)

		<details>
		  <summary>Good to know</summary>
		
		
		_Don't launch before you have a small following. The quality of upvotes is more important than the quantity and quality upvotes come from active PH users. Upvotes from new PH accounts will have a negative effect on your ranking. Besides upvotes, you also need lot's of engagement on your post to get to the front page, which usually comes from your early users and advocates._
		
		
		
		  </details>


		Add action item


			## 

			- [ ] 

		# 
		2. Build in public


		---

		- [ ] Create a [public roadmap](https://help.tally.so/roadmap)
		- [ ] Share your progress and keep a [change log](https://help.tally.so/changelog)
		- [ ] Create a Slack, Discord or other channel to talk to your users
		- [ ] Start a [blog](https://blog.tally.so/) and write about your product
		- [ ] Ask for feedback

		<details>
		  <summary>Templates for building in public</summary>
		
		
		
		_**Notion templates:**_
		_We used Super to create pretty URL's for our Notion pages._
		
		
		[Untitled](https://www.notion.so/3e52f26e7b8b4067ae04719cd2301cc1) 
		
		
		[Untitled](https://www.notion.so/ed00edca0f124696a07040022946fd9a) 
		
		
		
		_**Blog:**_
		
		
		_We created our_ [_blog & help_](https://blog.tally.so/) _center with_ [_Ghost_](https://ghost.org/) _and the help of the_ [_Ease theme_](https://iveel.co/ghost-themes/ease-ghost-theme)
		
		
		_**Feedback forms:**_
		
		
		_Use this_ [_feedback template_](https://tally.so/templates/t/E3Elme) _to share or embed a Tally form (for free)._ 
		
		
		
		  </details>


		Add action item


			## 

			- [ ] 

		# 
		3. Get ready for launch


		---


		## 🗓 Planning

		- [ ] Pick a date
		- [ ] Clear your calendar 1 day before, during and after

		<details>
		  <summary>Things to consider</summary>
		
		
		_Mondays to Thursdays are the most competitive days to post on PH, which makes the chance of becoming product of the day smaller, but you will likely get you more traffic than during weekends._
		
		
		_Clear your calendar for a couple of days, a good launch will get you lots of exposure, support questions and feedback. Make sure you have the time to exploit your launch._
		
		
		
		  </details>


		## 💬 Messaging

		- [ ] Prepare [social media posts](https://twitter.com/MarieMartens/timelines/1375072361121251330)
		- [ ] Prepare announcements for communities, channels and groups
		- [ ] Prepare an email update for your beta users

		<details>
		  <summary>Resources</summary>
		
		
		_Ask for feedback, not for upvotes._
		
		
		[Email example](7d1b5a86-a73a-4f86-8aaf-7ac2e73d5b61)
		
		
			![](https://s3.us-west-2.amazonaws.com/secure.notion-static.com/463c513e-5567-4d8f-85b5-ba955e8c3701/PH_launch_email.jpg?X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Content-Sha256=UNSIGNED-PAYLOAD&X-Amz-Credential=AKIAT73L2G45EIPT3X45%2F20220725%2Fus-west-2%2Fs3%2Faws4_request&X-Amz-Date=20220725T091458Z&X-Amz-Expires=3600&X-Amz-Signature=dea505614213cd9c11b8752fd31f667ed3582ee5e43d9f6e8f3c93a6118c3451&X-Amz-SignedHeaders=host&x-id=GetObject)
		
		
		
		  </details>


		## 🐱 Prepare PH post


		- [ ] Tagline 
		
		- [ ] Topics 
		
		- [ ] Download link 
		
		- [ ] Status 
		
		- [ ] Thumbnail 
		
		- [ ] Gallery 
		
		- [ ] Youtube video 
		
		- [ ] Description 
		
		- [ ] Promo 
		
		- [ ] Maker's comment 
		
		Very short description of the product
		
		Add 3 to 4 that strongly relate to the product
		
		Such as App store, Google Play, etc
		
		Is your product in beta or not?
		
		240x240 - JPG, PNG or GIF - 3MB
		
		1270x760 - [prepare at least 2 images](https://www.figma.com/file/35FXWEaawCWOYVI58k9DUA/PH-Launch?node-id=1%3A5https://www.figma.com/file/35FXWEaawCWOYVI58k9DUA/PH-Launch?node-id=1%3A5https://www.figma.com/file/35FXWEaawCWOYVI58k9DUA/PH-Launch?node-id=1%3A5)
		
		Optional, will be shown first in the gallery
		
		260 characters description of your product
		
		PH users like a promo code
		
		[Make it count!](/86f83c142afc4dd79ccf9ae9e795923e)


		<details>
		  <summary>Resources</summary>
		
		
		[Maker's comment](86f83c14-2afc-4dd7-9ccf-9ae9e795923e)
		
		
			_Briefly introduce yourself, the team, and the problem that you’re solving. Explain what the value prop is, what’s the use case, who it's for, and why you are building it. Conversation is important, so ask for feedback. Products that have active conversations generate more interest and tend to do well overall._
		
			- **Product:** Tally
			- **Tagline:** The simplest way to create forms for free
			- **Description:** Tally is a new type of form builder. Just start typing and build forms for all purposes in seconds. Without knowing how to code, and for free!
			- **Maker's comment:**
		
			Hi PH! 👋 
		
		
			Filip & Marie here, makers of Tally. Together with our early beta users, we've been working on a new exciting project for the last months. We're so stoked to share it with you today:  
		
		
		
			**Meet Tally, the simplest way to create forms for free.**
		
		
		
			🙋🏻‍♀️ **Why Tally?**
		
		
			As makers and frequent form users, we were unsatisfied with the existing tools out there. They either force you in a specific format or bombard you with countless limits and paywalls. We wanted a simple, yet powerful form builder that allows you to create any type of form without breaking the bank. We set off building Tally—a new type of form builder for makers and no-coders.
		
			- **Works like a doc:** Just start typing, Tally is a form builder that you will enjoy using. It makes form building easy and accessible to everyone. Use shortcuts to create any type of form in seconds. Take it for a spin, no sign-up needed.
			- **99% FREE:** We built Tally with a different business model in mind. Unlike other form builders, most advanced features are free and without limits.
			- **Tally Pro:** Simple pricing. Tally Pro offers empowering features tailored to the needs of teams and creators, at $29/month. 🙃
		
			🤩 **Powerful features for FREE**
		
		
			Unlimited forms, unlimited questions, unlimited responses, collect payments, file upload, custom logo & cover, custom "Thank you" pages, form logic, calculator, hidden fields, answer piping, Zapier integration, Google Sheets integration, email notifications, redirect on completion, schedule a close date, close on response limit, custom closed message, and many more.
		
		
			⚡️ **Tally Pro features**
		
		
			Team collaboration, workspaces, custom domains, no Tally branding, no payments commission, unlimited file uploads.
		
		
			🚀 **What’s next?** 
			Subscriptions, translations, pre-filled answers, partial submissions, Notion & Airtable integration, and more! Take a look at our [public roadmap](https://help.tally.so/roadmap) to see what features will be shipping soon.
		
		
			🤑 **Today's discount: 20% off Tally Pro** 
		
		
			To celebrate our PH launch we're offering **2**0% off Tally Pro, for the first 6 months. Use **MEOW20** at checkout, only redeemable today.
		
		
			💜 **Let us know what you think!**
		
		
			Tally is made from the heart and we couldn’t be more excited for you to check out our work. We would love to hear from you and get your thoughts on how to take our product to the next level. Feel free to leave a comment below, join us on [slack](https://tally.so/slack), or reach out via [email](mailto:hello@tally.so), anytime. 
		
		
			Marie & Filip
		
		
		[Figma template](1ea39cf7-26f6-4efd-8dea-bab90da87fa5)
		
		
			[embed](https://www.figma.com/embed?embed_host=notion&url=https%3A%2F%2Fwww.figma.com%2Ffile%2F35FXWEaawCWOYVI58k9DUA%2FPH-Launch%3Fnode-id%3D1%253A5)
		
		
		
		  </details>


		## 👩🏻‍💻 Updates

		- [ ] Update your [roadmap](https://help.tally.so/roadmap) 
		- [ ] Update your [landing page](https://tally.so) with the latest features and [social proof](https://twitter.com/TallyForms/timelines/1367501250930102278)
		- [ ] Make sure your analytics are in place to track all of that extra traffic


		Add action item


			## 

			- [ ] 

		# 4. Launch day


		---


		## ☕️ AM

		- [ ] Post on Product Hunt at **12.01 AM PST**
		- [ ] Update your website with a banner and/or add the [PH badge](https://help.producthunt.com/en/articles/2731371-how-to-add-a-product-hunt-badge-to-your-website)
		- [ ] Update your social media profiles with a link to your PH post
		- [ ] Send a first email batch to your users 
		- [ ] Share the news on social media
		- [ ] Post in your active slack groups, forums & communities 
			- [ ] [Indiehackers](https://www.indiehackers.com/group/product-hunt)
			- [ ] [Reddit](https://www.reddit.com/r/ProductHunters/) (or _/SideProject, /Entrepreneur, /Startup, /SmallBusiness)_
			- [ ] [Hackernews](https://news.ycombinator.com/show)
			- [ ] Others
		- [ ] Reply, reply, reply and reply to all comments

		<details>
		  <summary>Things to consider</summary>
		
		
		_**Timing:**_ _There is no single best time to post, but keep in mind that the homepage is based on a 24 cycle, and new products hit the homepage at 12:01am PST. Best practice to do it before 9am PST so there’s enough time for people to discover your product._
		
		
		_**Emailing:**_ _If you have a large user base, don't email all of them at once, but split your email campaign up in batches during the day._
		
		
		
		  </details>


		## 
		🍸 PM

		- [ ] Send the next email batches, spread over the day
		- [ ] Share your progress on social media
		- [ ] Keep the conversation going and try to keep up with comments 


		Add action item


			## 

			- [ ] 

		# 5. The day(s) after


		---


		## 📈 Measure the return

		- [ ] How many visitors did your website get?
		- [ ] How many extra users/subscribers did you gain?
		- [ ] How much money did you make?
		- [ ] How many followers did you gain on social media?

		## 👩🏻‍💻 Updates

		- [ ] Share your result with your followers/subscribers
		- [ ] [Congratulate](https://twitter.com/TallyForms/status/1369198314030313472?s=20) your competitors
		- [ ] Add your product to Product Hunt collections
		- [ ] Add your product as an alternative to similar products on PH
		- [ ] Let us know what helped your launch via the form below 💜

		[embed](https://tally.so/embed/wkbVe3?hideTitle=1&alignLeft=1)
		



[ML](f1615656-36ae-4532-aeb2-0d797008d793)


	Neural Network Cars and Genetic Algorithms 
	[https://www.youtube.com/watch?v=-sg-GgoFCP0&feature=youtu.be&ab_channel=ReadySetPython](https://www.youtube.com/watch?v=-sg-GgoFCP0&feature=youtu.be&ab_channel=ReadySetPython)


	[https://cleanup.pictures](https://cleanup.pictures/)


[Legal](65718fcb-a733-43e9-8258-3caa03bad020)


	[https://getterms.io](https://getterms.io/)


	[https://www.privacypolicygenerator.info](https://www.privacypolicygenerator.info/)


	[https://zegal.com/en-gb](https://zegal.com/en-gb/)


[Searchers](96adbfc2-18c1-403e-ae6a-48835249f369)


	[duckduckgo](https://duckduckgo.com/)


	[Open Hub Code Search](http://code.openhub.net/)


	[Code Search - Source Code Search Engine - NerdyData](https://search.nerdydata.com/code)


	[Яндекс](http://www.yandex.ru/)


	[百度一下，你就知道](http://www.baidu.com/)


	[Blippex](https://www.blippex.org/)


	[blekko | search](http://blekko.com/)


	[Wolfram|Alpha: Computational Knowledge Engine](http://www.wolframalpha.com/)


	[Bing](http://www.bing.com/)


	[Ask.com - ¿Cuál es tu pregunta?](http://es.ask.com/)


	[AOL.com - Netscape](http://netscape.aol.com/)


	[foofind.com](http://foofind.com/)


	[CC Search](http://search.creativecommons.org/)


	[Questions & Answers | ChaCha](http://www.chacha.com/)


	[Carrot2 Clustering Engine](http://search.carrot2.org/stable/search)


	[ODP - Open Directory Project](http://www.dmoz.org/)


	[Yahoo! Search - Web Search](http://search.yahoo.com/)


	[Search engine and human edited web directory KartOO](http://www.kartoo.com/)


	[Gennio Buscador | La red social de búsqueda nº 1 del mundo en español](http://www.gennio.com/)


	[MetaCrawler](http://www.metacrawler.com/)


	[Yippy.com - Yippy Search Engine](http://yippy.com/)


	[qwant](http://www.qwant.com/)


	[shodan](http://www.shodanhq.com/)


	[TinEye Reverse Image Search](http://tineye.com/)


[Tools](b682c53a-86c6-4d55-a6e3-d2af5b241fe4)


	[Terms and Conditions Generator | iubenda](https://www.iubenda.com/en/terms-and-conditions-generator?code=iubph20)


	---


	[https://lawof100.co/](https://lawof100.co/)


[Other brains](54e6cb96-4407-425a-a554-5984422b19e1)

	- [https://wiki.nikitavoloboev.xyz](https://wiki.nikitavoloboev.xyz/)
	- [https://garden.anthonyamar.fr](https://garden.anthonyamar.fr/)
	- [https://paul.copplest.one/knowledge/](https://paul.copplest.one/knowledge/business/management.html#tech-teams)
	- [https://github.com/costinEEST/almanacs](https://github.com/costinEEST/almanacs)
	- [https://wiki.dzx.cz](https://wiki.dzx.cz/)
	- [https://nkintc.gitbook.io/brainless](https://nkintc.gitbook.io/brainless/)
	- [https://publish.obsidian.md/allanmacgregor](https://publish.obsidian.md/allanmacgregor)
	- [https://notes.abhinavsarkar.net](https://notes.abhinavsarkar.net/)
	- [https://wiki.stultus.in](https://wiki.stultus.in/)
	- [https://notes.eddyerburgh.me](https://notes.eddyerburgh.me/)
	- [https://gordonbrander.com/pattern](https://gordonbrander.com/pattern/)
	- [https://www.are.na/tmm](https://www.are.na/tmm/)
	- [https://un.curl.dev/people/negative](https://un.curl.dev/people/negative)

[To watch](ade7c669-40d6-4ea9-b303-1b420dd22118)


	[30 Minutes That Will Change Your Perspective on Life | Kobe Bryant Motivation](06fe8a8f-0780-4182-b355-37fed5c2f0f7)


		[https://www.youtube.com/watch?v=Da-v4--Qn0U&ab_channel=MotivationMadness](https://www.youtube.com/watch?v=Da-v4--Qn0U&ab_channel=MotivationMadness)


	[Where Does Bad Code Come From?](50a8b156-df06-45af-a839-123e9a87c83b)


		[https://www.youtube.com/watch?v=7YpFGkG-u1w&ab_channel=MollyRocket](https://www.youtube.com/watch?v=7YpFGkG-u1w&ab_channel=MollyRocket)


	[Stop Over-Engenering](4344b365-8802-470f-bbd7-6680bc4858e9)


		[https://www.youtube.com/watch?v=GRr4xeMn1uU&ab_channel=BuildStuff](https://www.youtube.com/watch?v=GRr4xeMn1uU&ab_channel=BuildStuff)


	[Growing a Language, by Guy Steele](7b8fd6e0-2615-4b32-bbb2-2febf348d2ab)


		[https://www.youtube.com/watch?v=_ahvzDzKdB0&ab_channel=BillPugh](https://www.youtube.com/watch?v=_ahvzDzKdB0&ab_channel=BillPugh)


	[PLTalk: OCaml at Jane Street](13c0fe72-b995-4130-a2e0-46944bad1595)


		[https://www.twitch.tv/videos/1190375312](https://www.twitch.tv/videos/1190375312)


	[Watch Dependently Typed State Machines](320c6e01-6e64-45d0-9aaa-70be652bb75a)


		[https://www.youtube.com/watch?v=AgRmpMPCKeU&ab_channel=ComposeConference](https://www.youtube.com/watch?v=AgRmpMPCKeU&ab_channel=ComposeConference)


		[https://jeffas.io/2020/04/15/ocaml-state-machines/](https://jeffas.io/2020/04/15/ocaml-state-machines/)


		[https://codereview.stackexchange.com/questions/123723/finite-state-machine-written-in-ocaml-to-test-for-the-sequence-0-1](https://codereview.stackexchange.com/questions/123723/finite-state-machine-written-in-ocaml-to-test-for-the-sequence-0-1)


	[CSS Grid
	](a2b2f7e4-4d37-4022-af63-2fbe1d8b7dde)


		[https://courses.wesbos.com/account/access/60cb1a62259f7d62e7f6f13f](https://courses.wesbos.com/account/access/60cb1a62259f7d62e7f6f13f)


	[Game Theory 101 (#1): Introduction ](ddd50f55-8089-4c11-8f82-605ab4fae602)


		[https://www.youtube.com/watch?v=NSVmOC_5zrE&ab_channel=WilliamSpaniel](https://www.youtube.com/watch?v=NSVmOC_5zrE&ab_channel=WilliamSpaniel)


	[The Ultimate Guide to Investing in Stocks (2021)](cef5d4d4-355b-4715-9ff9-f3cfc70ed6a6)


		 [https://www.youtube.com/watch?v=gFQNPmLKj1k&ab_channel=AliAbdaal](https://www.youtube.com/watch?v=gFQNPmLKj1k&ab_channel=AliAbdaal)


	[Modeling domain with Reason](93e8d8f6-9a32-44da-aca9-8010b0326bd8)

		- [ ] Watch [https://www.youtube.com/watch?time_continue=293&v=2uV2CmTns9Q&feature=emb_title](https://www.youtube.com/watch?time_continue=293&v=2uV2CmTns9Q&feature=emb_title)
		- [ ] Condense an example of F#

	[Category Theory Knowledge](b5475a3d-2545-4291-801d-d8ba1aa878e6)


		### Playlist


		[https://www.youtube.com/watch?v=I8LbkfSSR58&list=PLbgaMIhjbmEnaH_LTkxLI7FMa2HsnawM_](https://www.youtube.com/watch?v=I8LbkfSSR58&list=PLbgaMIhjbmEnaH_LTkxLI7FMa2HsnawM_)


		[https://www.amazon.es/Algebra-Chapter-Graduate-Studies-Mathematics/dp/0821847813](https://www.amazon.es/Algebra-Chapter-Graduate-Studies-Mathematics/dp/0821847813)


		### Write notes


		---


		## Category Theory 1.1: Motivation and Philosophy


		## Category Theory 1.2: What is a category


	[Developer Tools Secrets That Shouldn't Be Secrets - Christian Heilmann](f5ed4d00-9447-4be6-948d-a1c3ee08e7f3)


		[https://www.youtube.com/watch?v=q_qzHzIVxw4&ab_channel=CITYJSCONFLONDON](https://www.youtube.com/watch?v=q_qzHzIVxw4&ab_channel=CITYJSCONFLONDON)


	[Artificial Consciousness and the Nature of Reality](674972a0-0041-4e2e-863d-22bb6183132b)


		[https://www.youtube.com/watch?v=P-2P3MSZrBM](https://www.youtube.com/watch?v=P-2P3MSZrBM)


	[Lightrun's Developer Productivity Masterclass](0d62fa77-8eae-4e00-95a9-6ede54f1fdd2)


		[https://www.youtube.com/watch?v=yVdfoX9Awrk](https://www.youtube.com/watch?v=yVdfoX9Awrk)


	[Time for a Change: Introducing irreversible time in economics](1563bb9a-25a6-474e-8f1c-33b3ae2b3773)


		[https://www.youtube.com/watch?v=f1vXAHGIpfc](https://www.youtube.com/watch?v=f1vXAHGIpfc)


	[How git works 2h](af83f34d-dd55-494b-9a51-f0e7ea4ae629)


		[https://www.youtube.com/watch?v=TZRS9llBBYU](https://www.youtube.com/watch?v=TZRS9llBBYU)


	[Vercel interviews svelte](5cc617a1-4f1b-4f38-94eb-c30a3ba787f3)


		[https://www.youtube.com/watch?v=uQntFkK8Z54](https://www.youtube.com/watch?v=uQntFkK8Z54)


	**The Weight of Gold**


	# Watched


	[OCaml Programming: Correct + Efficient + Beautiful](b5faad5b-6863-47da-9ca7-e1e31c58892a)


		 [https://www.youtube.com/playlist?list=PLre5AT9JnKShBOPeuiD9b-I4XROIJhkIU](https://www.youtube.com/playlist?list=PLre5AT9JnKShBOPeuiD9b-I4XROIJhkIU)


	[Architecture "Good Enough"](42743ce0-240e-4331-a86e-27297c49a103)


		[https://www.youtube.com/watch?v=PzEox3szeRc](https://www.youtube.com/watch?v=PzEox3szeRc)


	[The Algebra of Happiness by Prof. Scott Galloway](a1515a39-9729-4792-92b4-cf52d6edd94d)


	[Microservices at Netflix](ac8f7e48-2a47-43eb-a19c-e565e9ae9875)


		[https://www.youtube.com/watch?v=CZ3wIuvmHeM&ab_channel=InfoQ](https://www.youtube.com/watch?v=CZ3wIuvmHeM&ab_channel=InfoQ)


	[Secret of happines](0a60343c-7ec3-4d60-a760-f121f1558d56)


		[https://www.youtube.com/watch?v=sDH4mzsQP0w&ab_channel=AmericanEnterpriseInstitute](https://www.youtube.com/watch?v=sDH4mzsQP0w&ab_channel=AmericanEnterpriseInstitute)


	[Listen Full-Time Open Source](8752fd4e-178b-4747-9ddf-f00fc19d969a)


		[https://corecursive.com/067-zig-with-andrew-kelley/](https://corecursive.com/067-zig-with-andrew-kelley/)


	[ClojureScript in the Age of TypeScript — David Nolen](5ad0f7bc-df7c-4cf3-a4de-2299d1f9e5ff)


		[https://www.youtube.com/watch?v=3HxVMGaiZbc&ab_channel=ChariotSolutions](https://www.youtube.com/watch?v=3HxVMGaiZbc&ab_channel=ChariotSolutions)


	[ORM vs SQL](19942bd2-af22-44f9-9824-b7638b5c8a84)


		[https://www.youtube.com/watch?v=NEx3Bi-sBxE&ab_channel=CodelyTV-Redescubrelaprogramación](https://www.youtube.com/watch?v=NEx3Bi-sBxE&ab_channel=CodelyTV-Redescubrelaprogramaci%C3%B3n)


	[JSON Decoding in Elm](ea7a2d10-135c-41b3-957b-12b08bcc23dc)


		[https://www.youtube.com/watch?v=Ti_CdQcO3jg&ab_channel=JesseWarden](https://www.youtube.com/watch?v=Ti_CdQcO3jg&ab_channel=JesseWarden)


	[Notion Tour (Dashboard & Setup) - How I Organize My Life](aad95477-eaaf-4270-a76b-cff310bf1920)


		[https://www.youtube.com/watch?v=5Vl2mP0Ita4&ab_channel=KharmaMedic](https://www.youtube.com/watch?v=5Vl2mP0Ita4&ab_channel=KharmaMedic)


	[9 Passive Income Ideas](d2aac103-a4ed-4d14-9115-6f63407960ae)


		[https://www.youtube.com/watch?v=M5y69v1RbU0&t=3s&ab_channel=AliAbdaal](https://www.youtube.com/watch?v=M5y69v1RbU0&t=3s&ab_channel=AliAbdaal)


	[DDD made Dependently Typed](8b9d2941-7078-4ac4-bb9e-cd5505e93f64)


		[https://www.youtube.com/watch?v=QBj-4K-l-sg&ab_channel=AndorPenzes](https://www.youtube.com/watch?v=QBj-4K-l-sg&ab_channel=AndorPenzes)


	[47 Spectacular Notion Tips for Productivity 21m](ff052ca0-c44f-41a0-868c-0cb6ed6ccab8)


		[https://www.youtube.com/watch?v=8CkAGa9p_L4&ab_channel=CuriousRefuge](https://www.youtube.com/watch?v=8CkAGa9p_L4&ab_channel=CuriousRefuge)


	[LDN 5: Kris Jenkins: What is Functional Programming?](255fa32e-a1a9-42ec-8d8a-e1ae2f34f761)


		[https://www.youtube.com/watch?v=tQRtTSIpye4](https://www.youtube.com/watch?v=tQRtTSIpye4)


	[LDN Functionals #8: OCaml the Ultimate Config Format](0e11c51a-4945-45f1-bd5c-235e9cb79ecb)


		[https://www.youtube.com/watch?v=GT4mF7lu4U0](https://www.youtube.com/watch?v=GT4mF7lu4U0)


	[Discussion: Making Programming Language Parsers, etc (Q&A is in separate video).](6169bacc-5be5-4642-9b1f-28d5d693a1ac)


		[https://www.youtube.com/watch?v=MnctEW1oL-E&ab_channel=JonathanBlow](https://www.youtube.com/watch?v=MnctEW1oL-E&ab_channel=JonathanBlow)


	[Techniques for dealing with lack of motivation, malaise, depression](0617550c-69db-4f16-b336-c4babb2955b7)


		 [https://www.youtube.com/watch?v=i7kh8pNRWOo&ab_channel=JonathanBlow](https://www.youtube.com/watch?v=i7kh8pNRWOo&ab_channel=JonathanBlow)


	[The Magic of SQL ](01616fb8-2339-476f-93fe-af7de7aaed95)


		[https://www.youtube.com/watch?v=pB_nOIk3mmY&ab_channel=TheMagicofSQL](https://www.youtube.com/watch?v=pB_nOIk3mmY&ab_channel=TheMagicofSQL)


	[How to Think by André Staltz](49cbeeb0-40f9-44ea-afa7-5a6d34265343)


		 [https://www.youtube.com/watch?v=_fB8GRotdrc](https://www.youtube.com/watch?v=_fB8GRotdrc)


	[Friday night hack - Pokura Demo: Hasura & Pokemon ](a7f733e2-7a13-4a5c-95d4-86c3380cbd29)


		[https://www.youtube.com/watch?v=FLnjS-4790w&feature=youtu.be](https://www.youtube.com/watch?v=FLnjS-4790w&feature=youtu.be)


	[Immutabilty changes everything ](88ede697-bf76-48dd-80c0-83f243337182)


		[https://vimeo.com/52831373](https://vimeo.com/52831373)


	[André Staltz: Two Fundamental Abstractions - Uphill Conf 2018](33250661-7d73-4972-af6b-63dd1171d9db)


		 [https://www.youtube.com/watch?v=fdol03pcvMA](https://www.youtube.com/watch?v=fdol03pcvMA)


	[Unboxed Types for OCaml](b20b4abe-22d6-4be8-949f-036d01f7e16a)


		 [https://www.youtube.com/watch?v=RV-4Xddk0Yc&ab_channel=JaneStreet](https://www.youtube.com/watch?v=RV-4Xddk0Yc&ab_channel=JaneStreet)


	[SVG can do that?!](bf07dcd4-fb4f-40a2-85bb-436bed1afd40)


		[https://www.youtube.com/watch?v=ADXX4fmWHbo&ab_channel=Codegram](https://www.youtube.com/watch?v=ADXX4fmWHbo&ab_channel=Codegram)


	[Why Inline SVG is Best SVG](039fcf13-fb88-4fcc-be9e-d3134fd2baa2)


		[https://www.youtube.com/watch?v=af4ZQJ14yu8&ab_channel=FrontEndCenter](https://www.youtube.com/watch?v=af4ZQJ14yu8&ab_channel=FrontEndCenter)


	[LDN Functionals #2 Kris Jenkins : Elm](3f459feb-d993-49f1-9bed-571d1354b7f5)


		[https://www.youtube.com/watch?v=xN1-mtw1Fns](https://www.youtube.com/watch?v=xN1-mtw1Fns)


	["Fast Parser Combinator Library from Scratch in OCaml"](1ea30c6c-68e9-48cf-ab2e-f6d614186bd7)


		[https://www.youtube.com/watch?v=Y5IIXUBXvLs&ab_channel=TsodingVODs](https://www.youtube.com/watch?v=Y5IIXUBXvLs&ab_channel=TsodingVODs)


[To learn](51bfaceb-3eac-4763-ae1c-3eb10144dd4b)


	[Tipografía Digital](c12ff54e-a4c0-479f-803a-da774bcf80b7)


		[https://weareshifta.com/curso/desarrollo-de-tipografia-para-pantalla](https://weareshifta.com/curso/desarrollo-de-tipografia-para-pantalla)


	[Course Parser Algorithms](c3bbc5a4-602a-4057-88de-b22206f3894d)


		[http://dmitrysoshnikov.com/courses/parsing-algorithms/](http://dmitrysoshnikov.com/courses/parsing-algorithms/)


	[Mathematical Foundations of Computing](250ddc44-f2c1-412c-bd85-e55e1a9ec1e6)


		[https://learnaifromscratch.github.io/math.html](https://learnaifromscratch.github.io/math.html)


		[https://web.stanford.edu/class/cs103](https://web.stanford.edu/class/cs103/)


	[OCaml type-system](d35afb6e-71e3-4eb5-92eb-ef703cddf2ee)


		[https://stackoverflow.com/questions/15092139/ocaml-higher-kinded-polymorphism-abstracting-over-modules](https://stackoverflow.com/questions/15092139/ocaml-higher-kinded-polymorphism-abstracting-over-modules)


		 [https://discuss.ocaml.org/t/why-parametrized-types-are-not-supported-in-module-package-type/3115](https://discuss.ocaml.org/t/why-parametrized-types-are-not-supported-in-module-package-type/3115)


		Write those in Reason? Understand them in OCaml


		[https://github.com/jdan/ocaml-data-structures](https://github.com/jdan/ocaml-data-structures)


	[Compilers ](74917b46-8d0d-48b6-8836-6b1286b1ea9e)


		[https://github.com/keleshev/compiling-to-assembly-from-scratch](https://github.com/keleshev/compiling-to-assembly-from-scratch)


		[https://github.com/Isaac-DeFrain/simple-compiler](https://github.com/Isaac-DeFrain/simple-compiler)


		[https://www.cs.cornell.edu/courses/cs6120/2020fa/self-guided/](https://www.cs.cornell.edu/courses/cs6120/2020fa/self-guided/)


		[https://web.stanford.edu/class/cs143/](https://web.stanford.edu/class/cs143/)


	[Typeclass](d4cdfe94-9fbf-472b-b038-8bdbf359b19e)


		Read [https://lexi-lambda.github.io/blog/2021/03/25/an-introduction-to-typeclass-metaprogramming/](https://lexi-lambda.github.io/blog/2021/03/25/an-introduction-to-typeclass-metaprogramming/)


		Read [https://www.mseri.me/typeclass-ocaml](https://www.mseri.me/typeclass-ocaml/)


	[SQL](c7c542cf-de33-431b-a7ef-3f9f7752f3bd)


		[https://theartofpostgresql.com](https://theartofpostgresql.com/)


		[https://sqlbolt.com](https://sqlbolt.com/)


		https://www.sqlforhumans.com

