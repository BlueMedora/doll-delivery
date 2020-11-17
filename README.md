## Totally Credible Backstory

You are a nice old lady who delivers porcelain dolls on foot using your walker to residents in a neighborhood. Every day a nice young man fills your handbag with porcelain dolls and drops you off in a new neighborhood. There's nothing weird about these dolls. They are just normal dolls.

He also gives you a map of the neighborhood and an address of the neighbor to deliver the handbag of dolls to. The handbag is extremely heavy and you have a bad hip so you always try to minimize the walking distance from your beginning position to your destination. Your job is to determine the shortest path to take to deliver your handbag of dolls.

## Your Task

**Help the old lady by implementing a [PathFinder](path_finder.go) in the [Go](https://golang.org/doc/tutorial/getting-started) programming language.**

Your solution should produce the shortest path between any two houses in the neighborhood, given a starting location and a target location.

Include a set of executable tests for your solution. The following is a set of inputs for which the correct result is known:

![Neighborhood Map](https://raw.github.com/postnati/doll-delivery/master/neighborhood-map.png)

A [sample neighborhood](sample.go) is provided. Given:

	startLocation: "Kruthika's abode"
	targetLocation: "Craig's haunt"

the correct result is:

	distance: 31
	path: ["Kruthika's abode", "Brian's apartment", "Wesley's condo", "Bryce's den", "Craig's haunt"]

Hints:

* read about [Dijkstra's Algorithm](http://en.wikipedia.org/wiki/Dijkstra%27s_algorithm)
* find more interesting example data for test cases on the internet
