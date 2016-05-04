# C-Sharp-Trie
An implementation of the trie data structure in C#

##Usage

Create a new instance of the Trie

    var trie = new Trie(new [] {"hello", "help", "he-man", "happy", "hoppy", "tom"});

Add another word to the trie:

    trie.AddWord("hope");

Get autocomplete suggestions:

   var autoCompleteSuggestions = trie.GetAutocompleteSuggestions("ha");

##Make the Trie case-sensitive

    var trie = new Trie(new [] {"hello", True});

