# ece30862-project-step-1-a-compiler-for-a-simple-language-solved
**TO GET THIS SOLUTION VISIT:** [ECE30862 Project step 1-A compiler for a simple language Solved](https://www.ankitcodinghub.com/product/ece30862-project-step-1-a-compiler-for-a-simple-language-v1-01-solved/)


---

📩 **If you need this solution or have special requests:** **Email:** ankitcoding@gmail.com  
📱 **WhatsApp:** +1 419 877 7882  
📄 **Get a quote instantly using this form:** [Ask Homework Questions](https://www.ankitcodinghub.com/services/ask-homework-questions/)

*We deliver fast, professional, and affordable academic help.*

---

<h2>Description</h2>



<div class="kk-star-ratings kksr-auto kksr-align-center kksr-valign-top" data-payload="{&quot;align&quot;:&quot;center&quot;,&quot;id&quot;:&quot;122016&quot;,&quot;slug&quot;:&quot;default&quot;,&quot;valign&quot;:&quot;top&quot;,&quot;ignore&quot;:&quot;&quot;,&quot;reference&quot;:&quot;auto&quot;,&quot;class&quot;:&quot;&quot;,&quot;count&quot;:&quot;2&quot;,&quot;legendonly&quot;:&quot;&quot;,&quot;readonly&quot;:&quot;&quot;,&quot;score&quot;:&quot;5&quot;,&quot;starsonly&quot;:&quot;&quot;,&quot;best&quot;:&quot;5&quot;,&quot;gap&quot;:&quot;4&quot;,&quot;greet&quot;:&quot;Rate this product&quot;,&quot;legend&quot;:&quot;5\/5 - (2 votes)&quot;,&quot;size&quot;:&quot;24&quot;,&quot;title&quot;:&quot;ECE30862 Project step 1-A compiler for a simple language Solved&quot;,&quot;width&quot;:&quot;138&quot;,&quot;_legend&quot;:&quot;{score}\/{best} - ({count} {votes})&quot;,&quot;font_factor&quot;:&quot;1.25&quot;}">

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
            5/5 - (2 votes)    </div>
    </div>
Change log:

v1.01 Wording changes in the introductory text and high level actions section. Changes to the code generated for ret, retr var, print&lt;type&gt;, printv, call, callr v1.0, changes from 0.18. Use the popa instruction to clear the stack during a return. Coloring for previous changes removed. Overstruck text from previous changes is removed. These changes are colored blue. v0.18, changes from 0.17. “,” (commas) between arguments have been removed from statements.

They serve no purpose and add extra steps to the parsing. v0.17, changes from 0.16. Added peek, poke and swp to list of instructions in the High Level Actions of the Compiler section. Changed base print opcode to 144, it had been conflicting with the cmpe instruction. Removed crossed out text. Made ret, call and pushv opcodes no longer crossed out. Changed instructions that use pushv (retr , printv) to use it correctly. Change code for call and callr as a result of changes to pushv. Change the peek statement and peek bytecode to be typed. Cross out bytecode documentation and refer the reader to the interpreter document. Changes shown in green v0.16, changes from 0.15 Make all push types in compiler actions explicit. Simplified and better documentation of call and callr instruction compiler actions. Let the print statement print characters and numbers. Added a printv statement to print variables. Changed compiler actions for retr to push a variable value, not a literal value.

v0.15, changes from 0.14 Change compiler actions for ret, retr, jmp. Change the description and compiler actions for poke. Change the description for swp. Change the compiler actions for call and callr. v0.14, changes from 0.13 Add peek, poke and swp instructions. Change popm compiler actions.

Change callr compiler actions. Other small changes to wording.

v0.13, changes from 0.12 Add a count field to subr, call and callr to simplify code generation. v0.12 Changes from 0.11. Added a callr statement that takes a return type. Fix the generated code for this and for call to allow arguments to be pushed by the call. Add a retr that returns a value and update the reg. v0.11: changes from 0.10. Put typing into push operators. Put opcodes for compare operators. fix actions for call. Make declarations reserve a stack location. Remove redundant store instruction (popv does the same thing.) v0.10: changes from 0.0. Comparison operators (cmpe, cmplt, cmpgt) added. jump conditional (jmpc) added. bytecode values added. Font changed to Times New Roman.

This project builds a compiler for a small language. The input language is described below. The output language is a bytecode that is interpreted. You will be supplied a binary for the interpreter, and will write an interpreter as a second project.

High level organization of the language:

The first non-comment statement in the language is the start of the main routine. After the end of the main routine, other functions are declared and defined.

Within each function the first non-comment statements are variable declarations. All variable declarations must be at the top of the function.

The first non-declaration statement defines the start of the executable and label statements. The various statements are defined below.

At the end of the function there will be a ret statement. The next statement, if it exists, should be a new function.

Four kinds of values can be operated on by a program, in addition to labels. integer: 32 bit integer values. Specified as a string of decimal digits, i.e., 56. short: 16 bit integer values. specified as a string of decimal digits with an s appended, i.e., 56s.

float: 32 bit floating point values, specified as a string of decimal digits, a decimal point, and a fractional part, i.e., 56.04. char: these are only present in print statements and are always literals, e.g., ‘c’.

Native representations can be used for integers, shorts and floats. Operations, described below, can be applied to mixed values, i.e., a float and a short can be added and stored in an integer.

Details of different kinds of statements in programs are given in the section Input language below.

High level actions of the compiler:

The compiler will read each statement in turn from the source program file, and determine the operation the statement performs and the operands. Each statement has the structures

operation op op, …

i.e., and operation plus zero or more operands.

If the statement is a variable declaration, the compiler will create an entry in the symbol table . There is one symbol table for the entire program. The symbol table is a map whose key is one of two kinds. The first is a variable name, and the data for the variable name is the offset on the runtime stack (of the function the variable is declared in) for the variable. Clearly, the compiler needs to have a counter that keeps track of the number of variables declared in a function so that its runtime stack location is known. The second is a label number, where the data is the offset in the byte code of the label. Clearly, the compiler needs to have a counter that keeps track of the offset in the generated bytecode that the label is found.

For symbol table entries, (x) indicates the contents of the symbol table for the entry for key x.

After processing dec statements that only create entries in the symbol table and do not cause any code to be generated, the executable part of the function begins. The executable part of the function consists of lab, subr, ret, print, jmp, jmpc, cmpe, cmplt, cmpgt, call, push, popm, popv, peek, poke, swp, st, add, sub, mul and div.

At this time the program can be written to a file with an extension of .smp as a stream of bytes.

Input language.

The input language processes arithmetic expressions with numeric operations of +, -, *, and /. The bytecode representation of an operation is given by bc.op. For simplicity, the runtime stack contains one value in each position, i.e., a short and an int take the same amount of space. The runtime stack can be implemented as a vector whose elements point to objects containing the actual stack value.

Language statements:

The descriptions below give the semantics of the statement when the program is executed (which will be done by another program) and the code generated, or other actions taken, by this program. For all statements that generate byte codes an internal compiler counter giving the bytecode offset should be incremented appropriately. (x) indicates the contents of the symbol table for the entry for (x). Statements should all be parseable by a state machine/DFA.

All language statements fit on a single line.

/ string: A comment that can be ignored compiler actions: throw away the line of the program that is the comment.

decl var type: declares a variable whose name is given by var. The name will be 8 alpha characters or less. type is one of the three numeric types above, and are specified as int, short or float. All variables are local. There are no global variables.

compiler actions: create an entry in the symbol table (see below). The entry will be of the form &lt;key, value&gt;, where the key will be the concatenation of the function label of the function being compiled and var, and the value will be an object containing the stack offset within the stack frame of the function that will hold the variable and the type. The first variable declared in a function will have an offset of 0, the next an offset of 1, and so forth. Reserve a space in the stack for the variable by generating the following code:

push&lt;type&gt; 0

lab label: specifies a label that can be the target of a branch. label is a string with no more than eight alpha characters. compiler actions: Create an entry in the symbol table. The entry will be of the form &lt;key, value&gt;, where the key will be the concatenation of the function label of the function being compiled and label and the value will be the offset within the generated program code generated that the label appears.

subr cnt flabel: declares an flabel that is the start of a subroutine, where flabel is a string with no more than eight alpha characters. The main procedure always has the flabel of main. No two functions share the same flabel. cnt is the number of arguments subr takes and is an integer.

ret: a subroutine return. Pop all local variables off of the stack, pop the return value off of the stack and into the PC (program counter). The next statement to be executed will be the one indicated by the updated PC. compiler actions: Generate the following code:

pushi 0

bc.popa // 0 means pop everything and keep nothing

bc.ret // jmp to the location at the top of the stack – the return

// address

The previous code from 0.18 can be made to work, but Sara says the code above leads to a simpler implementation. I’ve included the previous code below (italicized) for reference.

bc.pop &lt;count of local variables added to the stack + count

of arguments&gt;

bc.ret // jmp to the location at the top of the stack – the return // address

retr var: a subroutine return that returns a variable value. Pop all local variables off of the stack, pop the return value off of the stack and into the PC (program counter). The next statement to be executed will be the one indicated by the updated PC. compiler actions: Generate the following code:

pushi (var)

bc.pushv&lt;type&gt; // type is the var type

pushi 1

bc.popa // pop all local variables off of the stack but return

variable bc.swp

bc.ret // jmp to the location at the top of the stack – the return

// address

The previous code from v0.18 can be made to work, but Sara says the code above leads to a simpler implementation. I’ve included the previous code below (italicized) for reference.

bc.pop &lt;count of local variables added to the stack + count

of arguments&gt; pushi (var)

bc.pushv&lt;type&gt; // type is the var

type bc.swp

bc.ret // jmp to the location at the top of the stack – the return // address

print&lt;type&gt; literal: prints the literal. Remember to increment the byte code offset in memory by the length of the literal in bytes. compiler actions: Generate the following code:

bc.push&lt;type&gt; literal bc.print&lt;type&gt;

printv var: prints the value of the variable compiler actions: Generate the following code:

bc.pushi (var)

bc.pushv&lt;type&gt; // type is the var bc.print&lt;type&gt;

jmp label: jump to the statement immediately following the label. The jmp statement pops the offset at the top of the stack off of the stack when it performs a jump.

compiler actions: Generate the following code:

pushi (label) bc.jmp

jmpc label: jump to the statement immediately following the label if the top of the stack has a

1, otherwise do nothing. Typically used after a compe, complt or compgt compiler actions: Generate the following code:

pushi (label) bc.jmpc

cmpe: Let t be a pointer to the top of the stack, the result of this is *t = *(t-1) == *t. 1 will be at the top of the stack if the comparison is true, 0 otherwise. The stack depth decreases by one at the end of this operation.

compiler actions: Generate the following code:

bc.cmpe

cmplt: Let t be a pointer to the top of the stack, the result of this is *t = *(t-1) &lt; *t. 1 will be at the top of the stack if the comparison is true, 0 otherwise. The stack depth decreases by one at the end of this operation. compiler actions: Generate the following code:

bc.cmplt

cmpgt: Let t be a pointer to the top of the stack, the result of this is *t = *(t-1) &gt;*t. 1 will be at the top of the stack if the comparison is true, 0 otherwise. The stack depth decreases by one at the end of this operation. compiler actions: Generate the following code:

bc.cmpgt

call cnt vara 0 vara2 … varan-1 flabel: jump to the subroutine specified by flabel, i.e., jump to the offset that is in the symbol table for the label. The address of the next instruction after the call is pushed onto the stack. cnt is the number of arguments passed to the subroutine, and is an integer. compiler actions:

If flabel is not in the symbol table, add it. You will not be able to add the location of flabel yet. Add the argument count, cnt, to the symbol table. If flabel is in the symbol table check that cnt is the same as the cnt in the symbol table. If not, print an error and terminate the compiler.

Generate the following code:

bc.pushi PC // compute the next instruction byte offset after the bc.pushi 6+2*n+x+1 // call. add the current instruction (PC)+8

/ non-arg push instructions + 2*n arg push

/ instructions +x positions taken by the arg values

/ and (flabel) value pushed

/ + 1 to skip past the last position to the / next instruction after the call.

/ 8+n+x+1 can be determined at compile time,

/ and the resulting integer variable pushed

/ the return argument varr which sits in the old stack

/ frame immediately before the arguments are pushed

bc.add bc.pushi (var0)

bc.pushv&lt;type&gt; // push the arguments (n pushes) bc.pushi (var1) bc.pushv&lt;type&gt;

. . . bc.pushi (varn-1) bc.pushi (flabel)

bc.pushi n+1 // compute the stack depth added by arguments,// (flabel) (n args + 1 for (flabel) bc.call

callr cnt varr vara 0 vara2 … varan-1 flabel: jump to the subroutine specified by flabel, i.e., jump to the offset that is in the symbol table for the label. cnt is the number of arguments passed to the subroutine, and is an integer. Space is reserved on the stack to hold the return value. After the call returns, the value in this stack location is moved to varr. The address of the next instruction after the call is pushed onto the stack. NOTE: varr must the same type for all calls and the type is set by the first call. compiler actions: Generate the following code:

If flabel is not in the symbol table, add it. You will not be able to add the location of flabel yet. Add the argument count, cnt, to the symbol table. If flabel is in the symbol table check that cnt is the same as the cnt in the symbol table. If not, print an error and terminate the compiler.

bc.pushi PC // compute the next instruction byte offset after the bc.pushi 8+2*n+x+1 // call. Add the current instruction (PC)+8

/ non-arg push instructions + 2*n arg push

/ instructions +x positions taken by the arg values

/ and (flabel) value pushed

/ + 1 to skip past the last position to the / next instruction after the call.

/ 8+n+x+1 can be determined at compile time,

/ and the resulting integer variable pushed

/ the return argument varr which sits in the old stack

/ frame immediately before the arguments are pushed

bc.add

bc.pushi (var0)

bc.pushv&lt;type&gt; // push the arguments (n pushes) bc.pushi (var1) bc.pushv&lt;type&gt;

. . . bc.pushi (varn-1) bc.pushv&lt;type&gt; bc.pushi (flabel)

bc.pushi n+1 // compute the stack depth added by arguments bc.call pushi (varr) bc.popv

push&lt;type&gt; val: push the val onto the stack. &lt;type&gt; specifies the type, either an s, i or f for short, int and float, respectively. The type of the operand to be pushed is inferred from the format of val.

compiler actions: Generate the following code:

bc.push&lt;type&gt; val

push&lt;type&gt; var: push the value of the variable whose name is given by var onto the stack. &lt;type&gt; specifies the type, either an s, i or f for short, int and float, respectively. The type of the operand to be pushed is inferred from the type of the variable. compiler actions: Generate the following code:

bc.pushs&lt;type&gt; (var)

popm val: pop the top entry val entries from the stack. The values in the stack are lost. val will be an integer.

compiler actions: Generate the following code:

bc.pushi val bc.popm

popv var: pop the current top of the stack and put the value into the variable var.

compiler actions: Generate the following code:

pushi (var) bc.popv

peek var val: var = stack[sp+val]. The types of the stack entry and the variable var must be the same. sp+val should be a valid stack entry. The primary use is to examine arguments. If there are n arguments then peek var, k-n get’s the value of the kth argument. val is typically negative compiler actions: Generate the following code:

pushi (var) pushi val bc.peek&lt;type&gt;

poke val var: stack[sp+val] = var. The types of the stack entry and the variable var must be the same. sp+val should be a valid stack entry. The primary use is to change the value of arguments. compiler actions: Generate the following code:

pushi (var) pushi val bc.poke&lt;type&gt; swp: Swap top two stack elements, i.e., t = stack[sp]; stack[sp] = stack[sp-1]; stack[sp-1] = t.

compiler actions: Generate the following code:

bc.swp

add: add the top two elements of the stack and push the result onto the stack. The stack depth decreases by one at the end of this operation. compiler actions: Generate the following code:

bc.add

sub: subtract the top two elements of the stack and push the result onto the stack. Thus, if t is a pointer to the top of the stack, the result of this is *t = *(t-1) – *t. The stack depth decreases by one at the end of this operation.

compiler actions: Generate the following code:

bc.sub

mul: multiply operand op1 and op2, and push the value onto the stack. he stack depth decreases by one at the end of this operation.

compiler actions: Generate the following code:

bc.mul

div: Divide the top two elements of the stack and push the result onto the stack. Thus, if t is a pointer to the top of the stack, the result of this is *t = *(t-1) / *t. The stack depth decreases by one at the end of this operation.

compiler actions: Generate the following code:

bc.div

Opcode values and meanings are found in the interpreter document.
