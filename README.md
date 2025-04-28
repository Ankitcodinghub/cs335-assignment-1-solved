# cs335-assignment-1-solved
**TO GET THIS SOLUTION VISIT:** [CS335 Assignment 1 Solved](https://www.ankitcodinghub.com/product/cs335-general-policies-solved/)


---

📩 **If you need this solution or have special requests:** **Email:** ankitcoding@gmail.com  
📱 **WhatsApp:** +1 419 877 7882  
📄 **Get a quote instantly using this form:** [Ask Homework Questions](https://www.ankitcodinghub.com/services/ask-homework-questions/)

*We deliver fast, professional, and affordable academic help.*

---

<h2>Description</h2>



<div class="kk-star-ratings kksr-auto kksr-align-center kksr-valign-top" data-payload="{&quot;align&quot;:&quot;center&quot;,&quot;id&quot;:&quot;115629&quot;,&quot;slug&quot;:&quot;default&quot;,&quot;valign&quot;:&quot;top&quot;,&quot;ignore&quot;:&quot;&quot;,&quot;reference&quot;:&quot;auto&quot;,&quot;class&quot;:&quot;&quot;,&quot;count&quot;:&quot;1&quot;,&quot;legendonly&quot;:&quot;&quot;,&quot;readonly&quot;:&quot;&quot;,&quot;score&quot;:&quot;5&quot;,&quot;starsonly&quot;:&quot;&quot;,&quot;best&quot;:&quot;5&quot;,&quot;gap&quot;:&quot;4&quot;,&quot;greet&quot;:&quot;Rate this product&quot;,&quot;legend&quot;:&quot;5\/5 - (1 vote)&quot;,&quot;size&quot;:&quot;24&quot;,&quot;title&quot;:&quot;CS335 Assignment 1 Solved&quot;,&quot;width&quot;:&quot;138&quot;,&quot;_legend&quot;:&quot;{score}\/{best} - ({count} {votes})&quot;,&quot;font_factor&quot;:&quot;1.25&quot;}">

<div class="kksr-stars">

<div class="kksr-stars-inactive">
            <div class="kksr-star" data-star="1" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" data-star="2" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" data-star="3" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" data-star="4" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" data-star="5" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
    </div>

<div class="kksr-stars-active" style="width: 138px;">
            <div class="kksr-star" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
    </div>
</div>


<div class="kksr-legend" style="font-size: 19.2px;">
            5/5 - (1 vote)    </div>
    </div>
• Create a zip file named “cs335_&lt;roll&gt;.zip”. The zipped file should contain a folder assign1 with the following files:

– Implementation files in your chosen implementation language.

– Four test case files containing proper non-trivial Java programs. You should name the test files as “test_&lt;serial number&gt;.java”.

– A script file named run.sh similar to the sample “run.sh” shared with this assignment problem. The script should generate an output file “test_&lt;serial number&gt;.out” with the desired output format, corresponding to an input file.

– A PDF file describing any tools that you used, and include compilation and execution instructions.

• You should use LATEX typesetting system for generating the PDF file.

• Submitting your assignments late will mean losing points automatically. You will lose 20% for each day that you miss, for up to two days.

Evaluation

• Please write your code such that the exact output format is respected (if any).

• We will evaluate your implementations on a Unix-like system, for example, a recent Debianbased distribution.

• We will evaluate the implementations with our own inputs and test cases, so remember to test thoroughly.

Problem 1 [50 points]

Create a lexer (i.e., scanner) for the Java language. The complete lexical structure for Java 8 is available here .

The output of the lexer should be a file containing a list of the form Lexeme | Token | Count.

1

Example

Input. Consider the following input Java program. public class Program {

/∗

∗ This i s my f i r s t java program .

∗/

public static void main ( String [ ] args ) { int data = 50; // d e c l a r a t i o n

boolean f l a g = false ;

}

}

Expected output. The output should (1) list and classify all unique lexemes into proper syntactic categories, and (2) provide a count of the 〈lexeme, token〉tuples.

Lexeme Token Count

public Keyword 2

class Keyword 1

Program Identifier 1

{ Separator 2

static Keyword 1

void Keyword 1

main Identifier 1

( Separator 1

String Identifier 1

[ Separator 1

] Separator 1

args Identifier 1

) Separator 1

int Keyword 1

data Identifier 1

= Operator 2

50 Literal 1

; Separator 2

} Separator 2

boolean Keyword 1

flag Identifier 1

false Literal 1

2
