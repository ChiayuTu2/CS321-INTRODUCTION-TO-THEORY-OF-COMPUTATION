<h1 align = 'center'>Summary</h1>

<h2 align = 'center'>Purpose</h2>
<p>Use your own understanding and online information to summarize what I learned in the CS 321 INTRODUCTION TO THEORY OF COMPUTATION class at Oregon state university in Winter 2024.

<h2 align = "center">Contents</h2>
<div>
    <p>📦Summary</p>
    <ul>
        <li>📄Language</li>
            <ul>
                <li>
            </ul>
    </ul>
</div>

<h2 align = 'center'>Language</h2>
    <ol>
        <li>Language : A language is a collection of strings composed of characters from a specific alphabet. (語言是由特定字母表中的字符組成的字符串集合。)
            <ul>
                <li>Concatenation of Strings (字符串的連接):
                    <ul>
                        <li>Def: The operation of joining two strings end-to-end to form a new string. (將兩個字符串首尾相連形成一個新字符串的操作)
                        <li>Exp: If you have strings "abc" and "def", their concatenation is "abcdef".
                    </ul>
                <li>Reverse (字符串的反轉):
                    <ul>
                        <li>Def: The operation of reversing the order of characters in a string. (將字符串中的字符順序顛倒的操作。)
                        <li>Exp: The reverse of the string "abc" is "cba".
                    </ul>
                <li>Concatenation of Languages (語言的連接):
                    <ul>
                        <li>Def: The operation of concatenating each string from two languages to form a new language. (對兩個語言中的每個字符串進行連接操作，形成一個新的語言。)
                        <li>Exp: If language L1 contains {"a", "b"} and L2 contains {"c", "d"}, then their concatenation is {"ac", "ad", "bc", "bd"}.
                    </ul>
                <li>Kleene Closure (克萊尼閉包) / Star Closure (星閉包):
                    <ul>
                        <li>Def: A new language that contains all possible strings formed by concatenating zero or more strings from the original language. (從一個語言出發，包含所有由原始語言中的字符串通過零次或多次連接形成的字符串的新語言。)
                        <li>Feat: Always includes the empty string, representing zero concatenations. (總是包括空字符串，表示零次連接。)
                        <li>Exp: If a language L contains {"a", "b"}, its Kleene Closure includes {"", "a", "b", "aa", "ab", "ba", "bb", "aaa", ...}.
                    </ul>
            </ul>
    </ol>

