# breezy
(WIP) Static Analyzer for Sway

## Tasks

- [ ] Familiarize yourself with the Sway language: Start by learning the syntax, semantics, and language constructs of Sway. This will help you understand the structure of Sway programs and the potential vulnerabilities they may have.
- [ ] Research existing static analysis techniques: Look into the current state-of-the-art in static analysis for smart contract languages, such as Slither for Solidity, and understand the different techniques and algorithms used.
- [ ] Create a parser: Create a parser that can translate Sway code into an abstract syntax tree (AST) representation. This will allow you to analyze the code in a more structured and organized way.
- [ ] Develop the analyzer: Use the AST to develop the static analyzer, implementing checks for known security vulnerabilities and best practices. This will include understanding the control flow of the code, checking for uninitialized variables, and identifying reentrancy bugs.
- [ ] Test and refine the analyzer: Test the analyzer on a variety of Sway programs to ensure it is working as expected and to identify any bugs or false positives. Use this feedback to refine and improve the analyzer.
- [ ] Document and distribute the analyzer: Create documentation and tutorials to help others understand how to use the analyzer, and distribute it via an open source license so that others can contribute to its development.

### Resources

* [slither](https://github.com/crytic/slither)

* [solstat](https://github.com/0xKitsune/solstat)

* [4naly3er](https://github.com/pynchmeister/4naly3er)


<img width="815" alt="Screen Shot 2023-01-30 at 11 29 22 AM" src="https://user-images.githubusercontent.com/33232379/215535567-81fd3ae7-e438-4632-8179-850ff29f43f9.png">

#### Notes

* Sway already has strong static analysis, keep a list of additional checks that can be added.
