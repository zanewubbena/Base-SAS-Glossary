# SAS Base Glossary


[Source Document](https://support.sas.com/documentation/cdl/en/mastergl/62860/HTML/default/viewer.htm#glossary.htm)


## A

***access descriptor***
    a SAS/ACCESS file that describes data that is managed by SAS, by a database management system, or by a PC-based software application such as Microsoft Excel, Lotus 1-2-3, or dBASE. After creating an access descriptor, you can use it as the basis for creating one or more view descriptors. See also SAS/ACCESS view and view descriptor. 

***access method***
    a set of instructions that an engine uses to read from or write to a file. 

***accessing SAS files***
    in the context of moving and accessing SAS files, the process whereby a user reads, writes, or updates SAS files that are stored on a different operating environment across a network. Such a user typically does not own the files. 

***across variable***
    in the REPORT procedure, a variable whose formatted values each form a column in the report. If the variable does not have a format, then each unformatted value forms a column. 

***active window***
    a window that is open and displayed, and to which keyboard input is directed. Only one window can be active at a time. 

***activities data set***
    in the CALENDAR procedure, a SAS data set that defines activities such as meetings and special events. The CALENDAR procedure displays these activities in a summary calendar or in a schedule calendar. See also schedule calendar and summary calendar. 

***aggregate storage location***
    a location on an operating system that can contain a group of distinct files. On different operating systems, different terms (such as directory, folder, or partitioned data set) are used to refer to an aggregate storage location. 

***alias***
    (1) an alternative name, usually in a shortened form, for a keyword, format, option, or other element of the SAS programming language or the SAS Component Language. (2) in the REPORT procedure, an alternate name for a report item. An alias enables you to set different characteristics for the same item when you use the item in more than one way in the report. 

***alignment form unit***
    a group of Xs printed in a rectangular block by the FORMS procedure. Alignment form units are the same size as the form units that they represent. They are used to test whether the output from the FORMS procedure will line up correctly on continuous-feed paper. See also form layout and form unit. 

***analysis variable***
    a numeric variable that is used to calculate statistics. An analysis variable usually contains quantitative or continuous values, but this is not required. 

***ANSI (American National Standards Institute)***
    an organization in the United States that coordinates voluntary standards and conformity to those standards. ANSI works with ISO to establish global standards. See also ISO (International Organization for Standardization). 

***architectural compatibility***
    a characteristic shared by two or more operating environments that use identical internal representations for storing numeric data, character data, or both. Compatible operating environments use the same standards or conventions for storing floating-point numbers (IEEE or IBM 390); for character encoding (ASCII or EBCDIC); for the ordering of bytes in memory (big Endian or little Endian); for word alignment (4-byte boundaries or 8-byte boundaries); and for data-type length (16- bit, 32-bit, or 64- bit). 

***argument***
    (1) in a SAS function or CALL routine, any of the values or expressions that a user supplies within parentheses and on which the function or CALL routine performs the indicated operation. (2) in syntax descriptions, any keyword in a SAS statement other than the statement name. (3) in macro processing, a character string that is used by a macro function. 

***arithmetic operator***
    any of the symbols (+, -, /, *, and **) that are used to perform addition, subtraction, division, multiplication, or exponentiation in SAS expressions. 

***array name***
    a name that is selected to identify a group of variables or temporary data elements. It must be a valid SAS name that is not the name of a variable in the same DATA step or SCL (SAS Component Language) program. 

***array reference***
    a reference to an element to be processed in an array. 

***ASCII collating sequence***
    the rules that are used by a specific ASCII encoding for sorting textual data. Sort order is determined by the location of each code point in the code page of an ASCII encoding. In the Windows Latin1 code page, the sort order of precedence is punctuation characters, numbers, uppercase characters, and lowercase characters. Because the uppercase A (code point 41) precedes the lowercase g (code point 67), A is sorted before g. See also EBCDIC collating sequence. 

***attribute***
    See variable attribute. 

***audit trail***
    an optional SAS file that you can create in order to log modifications to a SAS data file. Each time an observation is added, deleted, or updated, information is written to the audit trail about who made the modification, what was modified, and when. 

***autocall facility***
    a feature of SAS that enables you to store the source statements that define a macro and to invoke the macro as needed, without having to include the definition in your program. 

***autocall library***
    an aggregate storage location that contains individual library members, each of which contains a macro definition. See also aggregate storage location. 

***autocall macro***
    a macro whose uncompiled source code and text are stored in an autocall macro library. Unlike a stored compiled macro, an autocall macro is compiled before execution the first time it is called. 

***autoexec file***
    a file that contains SAS statements that are executed automatically when SAS is invoked. The autoexec file can be used to specify some of the SAS system options, as well as to assign librefs and filerefs to data sources that are used frequently. See also fileref and libref. 

***automatic join***
    a feature of the SQL Query Window that enables you to predefine join criteria for a specific set of tables. When you select these tables for a query in a future session, the join criteria are already defined and are ready for use. 

***automatic lookup***
    a feature of the SQL Query Window that automatically displays the values of a particular column when that column is selected in the WHERE EXPRESSION window. 

***automatic lookup table***
    a SAS data set that stores information that the SQL Query Window uses to determine how to perform automatic lookup. See also automatic lookup. 

***automatic macro variable***
    a macro variable that is defined by SAS rather than by the user and that supplies information about the SAS session. For example, the SYSPROCESSID automatic macro variable contains the process ID of the current SAS process. 

***automatic variable***
    a variable that is created automatically by the DATA step, some DATA step statements, some SAS procedures, and the SAS macro facility. 

## B

***backward compatibility***
    the ability of a SAS client that runs a particular version of SAS (such as SAS 9 or SAS 8) to read, write, and update a SAS file that was created using an earlier version of SAS (such as SAS 6) as long as the client's application does not implement new features such as long names. The SAS client and application that run the later version are said to be backward compatible with the SAS file that was created using the earlier version. See also forward compatibility. 

***base data set***
    in the COMPARE procedure, a SAS data set that is used as the basis of a comparison. 

***base version***
    the most recently created version of a generation data set. The name of the base version does not include the four-character suffix that indicates a generation ***number. See also generation data set. 

***batch job***
    a job (program) that is submitted to the operating system for batch processing. See also batch mode.

***batch mode***
    a method of executing SAS programs in which a file that contains SAS statements plus any necessary operating environment commands is submitted to the computer's batch queue. After you submit the program, control returns to your computer, and you can perform other tasks. Batch mode is sometimes referred to as running in the background. The program output can be written to files or printed on an output device. 

***BIDI text***
    See bidirectional text. 

***bidirectional text***
    a mixture of characters that are read from left to right and characters that are read from right to left. Most Arabic and Hebrew strings of text, for example, are read from right to left, but numbers and embedded Western terms within Arabic and Hebrew text are read from left to right. Short form: BIDI text. 

***big endian***
    a term that is used to describe the order in which a sequence of bytes is stored in computer memory (byte ordering). On big endian platforms, the value 1 is stored in binary and is represented in hexadecimal notation. One byte is stored as 01, two bytes as 00 01, and four bytes as 00 00 00 01. The most significant value in the sequence is stored first. In the SAS System, the following platforms are considered big endian: IBM mainframe, HP-UX, AIX, and Solaris. See also little endian. 

***binary file***
    a file that contains information that can be read by one or more software applications but not by humans. Some binary files are executable programs. Others store images, sounds, data, or a combination of printable and non-printable characters. Binary files cannot be edited with a text editor. 

***bit mask***
    a string of bits that has a specific pattern of binary 0s and 1s that you use to compare with other values. 

***block***
    (1) a unit of physical storage on disk or tape that is used for transferring data between an operating system or an application program and the storage media. (2) a group of compressed observations in an SPD Engine data set. If an application is thread- enabled, it can read, write, and process the observations faster when they are delivered as a block than when they are delivered as individual observations. See also observation and thread. 

***BMDP engine***
    the SAS engine that provides read-only access to BMDP files. BMDP is a library of statistical analysis programs that were originally developed at the UCLA Health Sciences Computing Facility. 

***Boolean operator***
    another term for logical operator. See also logical operator.

***border***
    a line that helps define the boundaries of a window. 

***box plot***
    a plot that displays summary statistics for the distribution of values for a variable. In the output from the UNIVARIATE procedure, dashed lines (- -) represent quartiles; a plus sign (+) represents the mean; and vertical lines (|), zeroes, and asterisks (*) represent values outside the box. 

***break***
    in the REPORT procedure, a section of the report that does one or more of the following: visually separates parts of the report; summarizes statistics and computed variables; displays text; displays values that have been calculated for a set of rows of the report; executes DATA step statements. You can create breaks when the value of a selected variable changes or at the beginning or end of a report. See also break variable. 

***break line***
    in the REPORT procedure, a line of a report that contains one or more of the following: characters that visually separate parts of the report; summaries of statistics and computed variables (called a summary line); text; values that have been calculated for a set of rows of the report. 

***break variable***
    in the REPORT procedure, a group variable or order variable that you select in order to specify the location of break lines. The REPORT procedure performs the actions that you specify for the break each time the value of the break variable changes. 

***buffer***
    an area of computer memory that is reserved for use in performing input/output (I/O) operations. 

***BY group***
    a group of observations or rows that have the same value for a variable that is specified in a BY statement. If more than one variable is specified in a BY statement, then the BY group is a group of observations that have a unique combination of values for those variables. 

***BY value***
    the value of a BY variable. 

***BY variable***
    a variable that is named in a BY statement and whose values define groups of observations to process. 

***BY-group processing***
    the process of using the BY statement to process observations that are ordered, grouped, or indexed according to the values of one or more variables. Many SAS procedures and the DATA step support BY-group processing. For example, you can use BY-group processing with the PRINT procedure to print separate reports for different groups of observations in a single SAS data set. 

## C

***calculated column***
    in a query, a column that does not exist in any of the tables that are being queried, but which is created as a result of a column expression. See also column expression. 

***calendar data set***
    in the CALENDAR procedure, a SAS data set that defines one weekly work schedule. Observations in a calendar data set must use character variables named _SUN_, _MON_, _TUE_, _WED_, _THU_, _FRI_, and _SAT_ to specify which workshift applies to which day of the week. 

***CALL routine***
    a component of the SAS programming language that changes the values of variables or performs other system operations. CALL routines are similar to functions except that you cannot use CALL routines in assignment statements. All SAS CALL routines are invoked with CALL statements. That is, the name of the routine must follow the keyword CALL in the CALL statement. 

***carriage-control character***
    a symbol that tells a printer how many lines to advance the paper, when to begin a new page, when to skip a line, and when to hold the current line for overprinting. 

***Cartesian product***
    a type of join that matches each row from each joined table to each row from all other joined tables. See also cross join and join. 

***catalog***
    See SAS catalog. 

***catalog entry***
    See SAS catalog entry. 

***catalog reference***
    a name that is temporarily associated with a catalog or with concatenated catalogs. You use a CATNAME statement to assign a catref. Short form: catref. 

***category***
    in the TABULATE procedure, the combination of unique values of class variables. The TABULATE procedure creates a separate category for each unique combination of values that exists in the observations of the data set. Each category that PROC TABULATE creates is represented by one or more cells in the table where the pages, rows, and columns that describe the category intersect. 

***catref***
    See catalog reference. 

***CEDA***
    See Cross-Environment Data Access. 

***cell***
    in general, the intersection of a row and a column in a table. In some SAS procedures such as PROC TABULATE and PROC FREQ, the value of each cell is a summary statistic for the input data set. The contents of the cell are described by the page, row, and column that contain the cell. 

***central processing unit***
    the main hardware component of a computer. The CPU executes program instructions and controls the operation of other parts of the computer. Short form: CPU. 

***character comparison***
    a process in which character operands are compared character by character from left to right, yielding a numeric result. If the character operands are equal, the result is the value 1; if they are not equal, the result is the value 0. 

***character constant***
    a character string that is enclosed in quotation marks in a SAS statement to indicate a fixed value rather than the name of a variable. The maximum number of characters that is allowed is 32,767. Character constants are sometimes referred to as character literals. See also character string. 

***character format***
    a set of instructions that tell SAS to use a specific pattern for writing character data values. 

***character function***
    a type of function that enables you to manipulate, compare, evaluate, or analyze character strings. 

***character informat***
    a set of instructions that tell SAS to use a specific pattern for reading character data values into character variables. 

***character literal***
    another term for character constant. See also character constant.

***character set***
    the set of characters that are used by a language or group of languages. A character set includes national characters, special characters (such as punctuation marks and mathematical symbols), the digits 0-9, and control characters that are needed by the computer. Most character sets also include the unaccented upper- and lowercase letters A-Z. See also national character. 

***character string***
    one or more alphanumeric characters or other keyboard characters or both. See also character constant.

***character value***
    a value that can contain alphabetic characters, the numeric characters 0 through 9, and other special characters. 

***character variable***
    a variable whose values can consist of alphabetic characters and special characters as well as numeric characters. 

***check box***
    an item in a window that you can select without affecting any other items. You can deactivate a check box by selecting it again. 

***class variable***
    a variable that is used to group (or classify) data. Class variables can have either character values or numeric values. Class variables can have continuous values, but they typically have a few discrete values that define the classifications of the variable. See also continuous variable and discrete variable. 

***client***
    a computer or application that requests services, data, or other resources from a server. See also server.

***client session***
    a SAS session that is running on a client computer. A client session accepts SAS statements and passes those that are submitted to the server for processing. The client session manages the output and messages from both the client session and the server session. 

***code page***
    an ordered table that shows the characters within a character set, along with their unique numeric representations. A code page captures an encoding, which results from applying an encoding method to a character set. For example, the German EBCDIC code page contains the encoding that results from applying the EBCDIC encoding method to the German character set. See also code point, character set, and encoding. 

***code position***
    the row and column location of a character in a code page. See also code page.

***code table***
    another term for code page. See also code page.

***collating sequence***
    a set of rules that determine how textual data is ordered and compared. See also EBCDIC collating sequence. 

***column***
    in relational databases, a vertical component of a table. Each column has a unique name, contains data of a specific type, and has certain attributes. A column is analogous to a variable in SAS terminology. 

***column alias***
    a temporary, alternate name for a column. Aliases are optionally specified in the SQL procedure's SELECT clause to name or rename columns. An alias is one word. See also column. 

***column dimension***
    in the TABULATE procedure, the combination of variables, variable values, and statistics that determine the number and arrangement of columns in the table. See also dimension and dimension expression. 

***column expression***
    (1) a set of operators and operands that, when evaluated, result in a single data value. The resulting data value can be either a character value or a numeric value. (2) in the TABULATE procedure, the part of the TABLE statement that determines the content and appearance of the column dimension by specifying the combination of variables, variable values, and statistics that make up that dimension. 

***column input***
    in the DATA step, a style of input in which column numbers are included in the INPUT statement to tell SAS which columns contain the values for each variable. This style of input is useful when the values for each variable are in the same location in all records. 

***column output***
    in the DATA step, a style of output that specifies column numbers in the PUT statement for writing data in fixed columns. 

***column percentage***
    the ratio of a sum or frequency count for a single cell of a table to the total sum or frequency count for the column that contains that cell. This ratio is represented as a percentage. 

***column-binary data storage***
    an older form of data storage that is no longer widely used and is not needed by most SAS users. Column-binary data storage compresses data so that more than 80 items of data can be stored on a single punched card. Because multi-punched decks and card-image data sets remain in existence, SAS provides informats for reading column-binary data. See also column-binary informat. 

***column-binary informat***
    a set of instructions that tell SAS how to read data that is stored in column-binary or multi-punched form into character and numeric variables. See also column-binary data storage. 

***command***
    a keyword that gives instructions to the host operating system or to the SAS windowing environment. 

***command-style macro***
    a macro that is defined with the CMD option in the %MACRO statement. See also statement-style macro and name-style macro.

***comparison data set***
    in the COMPARE procedure, a SAS data set that the procedure compares to a base data set. 

***compatible operating environments***
    See architectural compatibility. 

***compilation***
    the process of checking syntax and translating a portion of a program into a form that the computer can execute. 

***composite index***
    an index that locates observations in a SAS data set by examining the values of two or more key variables. See also simple index. 

***compute block***
    in the REPORT procedure, the statements that appear in one COMPUTE window or between one pair of COMPUTE and ENDCOMP statements. A compute block can be used to calculate a computed variable, to define display attributes for a report item, or to generate a customized report summary. 

***computed variable***
    in the REPORT procedure, a variable whose value is calculated by statements that are entered in the COMPUTE window. 

***condition***
    (1) in a SAS program, one or more numeric or character expressions that result in a value upon which some decision depends. (2) in the SQL procedure, the part of the WHERE clause that contains the search criteria. In the condition, you specify which rows are to be retrieved. 

***configuration file***
    an external file that contains SAS system options. These system options take effect each time you invoke SAS. See also external file. 

***configuration option***
    a SAS system option that can be specified in the SAS command or in a configuration file. Configuration options affect how SAS interacts with the computer hardware and operating system. 

***continuous variable***
    a variable that theoretically could have an uncountable number of possible values. For example, a variable that measures the temperature of water in degrees Celsius under normal conditions is continuous because it can have any value from 0 to 100, even though the thermometer that is used is not able to measure temperatures beyond a particular level of decimal precision. 

***controller***
    a computer component that manages the interaction between the computer and a peripheral device such as a disk or a RAID. For example, a controller manages data I/O between a CPU and a disk drive. A computer can contain many controllers. A single CPU can command more than one controller, and a single controller can command multiple disks. 

***converting SAS files***
    the process of changing the format of a SAS file from the format that is appropriate for one version of SAS to the format that is appropriate for another version in the same operating environment. 

***copy***
    to create a duplicate of a SAS file or observation or of a set of lines in a text editor window. Copying SAS data sets might change the format in which the file is stored if you use a different engine for the output data set. 

***copying SAS files***
    in the context of moving and accessing SAS files, the process of transferring SAS files between compatible operating environments, either by means of a magnetic medium or across a network. No transporting or converting is performed. See also converting SAS files, moving SAS files, and transporting SAS files. 

***correlation***
    a relationship between two variables in which there is a tendency for the values of one variable to become larger or smaller as the values of the other variable increase or decrease. 

***correlation coefficient***
    a statistic that measures the strength of the linear relationship between two series of values. The values of correlation coefficients range from -1 to 1. 

***CPU***
    See central processing unit. 

***CPU time***
    the amount of time it takes for the central processing unit of a computer system to perform the calculations or other operations that you request. 

***CPU-bound application***
    an application whose performance is constrained by the speed at which computations can be performed on the data. Multiple CPUs and threading technology can alleviate this problem. 

***cross join***
    a type of join that returns the product of joined tables. A cross join is functionally the same as a Cartesian product. See also Cartesian product and join. 

***Cross-Environment Data Access***
    a feature of SAS software that enables a SAS data file that was created in any directory-based operating environment (for example, Solaris, Windows, HP-UX, OpenVMS) to be read by a SAS session that is running in another directory-based environment. You can access the SAS data files without using any intermediate conversion steps. Short form: CEDA. See also data representation, foreign file format, and native file format. 

***crossing***
    in the TABULATE procedure, the process that combines the effects of two or more elements. 

***crosstabulation table***
    a frequency table that shows combined frequency distributions or other descriptive statistics for two or more variables. See also frequency table. 

***cumulative frequency***
    the total number of observations in all ranges up to and including a given range. 

***cumulative percent***
    the percentage of observations in all ranges up to and including a given range. 

## D

***data control block***
    on IBM mainframe operating systems such as z/OS and OS/390, a storage area that contains information about the physical characteristics of an operating system data set. Short form: DCB. 

***data error***
    a type of execution error that occurs when a SAS program analyzes data that contains invalid values. For example, a data error occurs if you specify numeric variables in the INPUT statement for character data. SAS reports these errors in the SAS log but continues to execute the program. See also programming error and syntax error. 

***data partition***
    a physical file that contains data and which is part of a collection of physical files that comprise the data component of a SAS Scalable Performance Data Engine data set. See also partition and partitioned data set. 

***data precision***
    the reliability of numeric data in a SAS file that is exchanged between operating environments. Compatible operating environments, which use the same internal representation for storing floating-point numeric data, exchange numeric data with no loss of precision. Precision is lost when numeric data is passed between incompatible operating environments. See also architectural compatibility. 

***data representation***
    the form in which data is stored in a particular operating environment. Different operating environments use different standards or conventions for storing floating-point numbers (for example, IEEE or IBM 390); for character encoding (ASCII or EBCDIC); for the ordering of bytes in memory (big Endian or little Endian); for word alignment (4-byte boundaries or 8-byte boundaries); and for data-type length (16-bit, 32-bit, or 64-bit). 

***data set***
    See SAS data set. 

***data set label***
    in a SAS data set, a user-defined attribute of up to 200 characters that is used for documenting the SAS data set. 

***DATA step***
    in a SAS program, a group of statements that begins with a DATA statement and that ends with either a RUN statement, another DATA statement, a PROC statement, the end of the job, or the semicolon that immediately follows lines of data. The DATA step enables you to read raw data or other SAS data sets and to use programming logic to create a SAS data set, to write a report, or to write to an external file. 

***DATA step interface***
    a feature of SAS software that enables you to use the DATA step to interact with other components of SAS such as the macro facility or the Output Delivery System (ODS). 

***DATA step variable***
    name of a location in memory where data is stored. DATA step variables appear in the DATA step. 

***DATA step view***
    a type of SAS data set that consists of a stored DATA step program. A DATA step view contains a definition of data that is stored elsewhere; the view does not contain the physical data. The view's input data can come from one or more sources, including external files and other SAS data sets. Because a DATA step view only reads (opens for input) other files, you cannot update the view's underlying data. 

***data transformation***
    the process of changing a data value from one form to another (for example, a calendar date to a SAS date value or vice versa). 

***data type conversion***
    a numeric-to-character or character-to-numeric conversion that SAS performs automatically. 

***data value***
    a unit of character or numeric information in a SAS data set. A data value represents one variable in an observation. For example, the variable LASTNAME might contain the data value Smith. 

***data view***
    See SAS data view. 

***database***
    an organized collection of related data. A database usually contains named files, named objects, or other named entities such as tables, views, and indexes. 

***database management system***
    a software application that enables you to create and manipulate data that is stored in the form of databases. Short form: DBMS. 

***date and time format***
    the instructions that tell SAS how to write numeric values as dates, times, and datetimes. 

***date and time informat***
    the instructions that tell SAS how to read numeric values that are represented as dates, times, and datetimes. 

***date value***
    See SAS date value. 

***datetime value***
    See SAS datetime value. 

***DBCS***
    See double-byte character set. 

***DBMS***
    See database management system. 

***DCB***
    See data control block. 

***declarative statement***
    a statement that supplies information to SAS and that takes effect when the system compiles program statements. 

***default directory***
    the directory that you are working in at any given time. When you log in, your default directory is usually your home directory. 

***delimiter***
    a character that serves as a boundary that separates the elements of a character string, a program statement, a data line, or a list of arguments. 

***delimiter-sensitive data***
    data in which the individual data values contain embedded delimiters, such as quotation marks, commas, and tabs. Short form: DSD. 

***denominator***
    the part of a fraction that is below the dividing line. 

***denominator definition***
    an expression or group of expressions that tell the TABULATE procedure what values to use for calculating the denominator of a percentage. Omitting the denominator definition tells PROC TABULATE to calculate the percentage of the value in one cell in relation to the total for all categories in the table. 

***descriptive statistic***
    a quantity that characterizes, rather than draws inference from, a collection of values. Types of descriptive statistics are measures of central tendency, measures of variation among values, and measures of the shape of the distribution of values. 

***descriptor information***
    information about the contents and attributes of a SAS data set. For example, the descriptor information includes the data types and lengths of the variables, as well as which engine was used to create the data. SAS creates and maintains descriptor information within every SAS data set. 

***destination***
    See ODS destination. 

***detail record***
    one of the two types of records found in a hierarchical file. In a hierarchical file, related data occur in groups. Each record group begins with a header record and usually contains one or more detail records. For example, in a customer order file, a header record may contain name and address information about the customer, and each detail record may contain information about an item ordered. 

***detail report***
    output that lists all the data that is processed. 

***detail row***
    in the REPORT procedure, a row of a report that contains information from a single observation in the data set or which consolidates the information for a group of observations that have a unique combination of values for all group variables. 

***device-based graphic***
    a graph created with SAS/GRAPH software for which a user-specified or default device (DEVICE= option) controls certain aspects of the graphical output. 

***dialog box***
    in a graphical user interface, a type of window that opens to prompt you for additional information or to ask you to confirm a request. 

***DICTIONARY table***
    a read-only SAS data view that contains information about SAS data libraries, SAS data sets, SAS macros, and external files that are either in use or available in the current SAS session. The DICTIONARY table also contains the settings for SAS system options that are currently in effect. 

***dimension***
    in the TABULATE procedure, the page, row, or column portion of a table. See also dimension expression, column dimension, row dimension, and page dimension. 

***dimension expression***
    in the TABULATE procedure, the portion of the TABLE statement that defines the content and arrangement of the rows, columns, or pages of the table. See also dimension, column dimension, row dimension, and page dimension. 

***direct access***
    in table lookup applications, a technique for retrieving records by observation number instead of searching a data set sequentially to find a match. This technique cannot be used with a BY statement, a WHERE statement, or a WHERE= data set option. It also cannot be used with transport format data sets, compressed data sets, data sets that are in sequential format on tape or disk, or SAS/ACCESS views or the SQL procedure views that read data from external files. 

***directory***
    on some operating systems, a unit of storage for files or a unit that catalogs information about files. See the appropriate SAS Companion for a technical description of directories on your host operating system. 

***directory listing***
    a list of members of a SAS data set or of entries in a SAS catalog, along with information about them. 

***discrete variable***
    a variable that has a countable number of possible values within the measurement range. For example, a variable that counts how often an event occurs over a period of time is discrete because the variable can have only integer values that are less than a realistic maximum value. See also continuous variable. 

***disk***
    a device for data storage that enables you to access any record on the disk directly. Disk storage differs from tape storage, which enables only sequential processing of records. 

***display variable***
    in the REPORT procedure, a variable that does not affect the order of the rows of the report. A report that contains one or more display variables has a detail row for each observation in the data set. By default, the REPORT procedure treats character variables as display variables. 

***distinct value***
    a value that occurs one or more times for a particular column in a table or for a particular variable in a data set. In a list of distinct values, each value is listed only once, no matter how many times it occurs in the table or data set. 

***DO group***
    a sequence of statements that starts with a simple DO statement and that ends with a corresponding END statement. See also DO loop. 

***DO loop***
    a sequence of statements that starts with an iterative DO, DO WHILE, or DO UNTIL statement and that ends with a corresponding END statement. The statements are executed (usually repeatedly) according to directions that are specified in the DO statement. See also DO group. 

***DOCUMENT destination***
    a SAS Output Delivery System (ODS) destination that produces a hierarchy of output objects. The DOCUMENT destination enables you to render multiple ODS output formats without rerunning a PROC step or DATA step, and it gives you more control over the structure of the output. See also ODS destination. 

***double trailing at sign***
    a special symbol @@ that is used to hold a line of data in the input buffer during multiple iterations of a DATA step. 

***double-byte character set***
    any East Asian character set (Japanese, Korean, Simplified Chinese, and Traditional Chinese) that requires a mixed-width encoding because most characters occupy more than one byte of computer memory or storage. This term is somewhat misleading because not all characters in a DBCS require more than one byte, and some DBCS characters actually require four bytes. Short form: DBCS. See also character set. 

***DSD***
    See delimiter-sensitive data. 

***dummy macro***
    a macro that the macro processor compiles but does not store. 

***duration***
    a value that represents the difference, in elapsed time or days, between any two time or date values. 

## E

***EBCDIC collating sequence***
    the rules that are used by a specific EBCDIC encoding for sorting textual data. Sort order is determined by the location of each code point in the code page of an EBCDIC encoding. For example, in the German EBCDIC code page, the sort order of precedence is punctuation characters, numbers, uppercase characters, and lowercase characters. Because the German uppercase letter Ä (code point 4A) precedes lowercase g (code point 87), Ä is sorted before g. See also collating sequence. 

***efficiency***
    the ability to obtain more results from fewer human or computer resources. 

***elapsed time***
    the amount of clock time needed to receive the result of a computer program, including time used by the computer to execute your program and the time your program spends waiting for resources (such as memory or a printer). Elapsed time is also known as throughput. 

***encoding***
    a set of characters (letters, East Asian logograms, digits, punctuation marks, symbols, and control characters) that have been mapped to hexadecimal values (called code points) that can be used by computers. An encoding results from applying an encoding method to a specific character set. Groups of encodings that apply the same encoding method to different character sets are sometimes referred to as families of encodings. For example, German EBCDIC is an encoding in the EBCDIC family, Windows Cyrillic is an encoding in the Windows family, and Latin 1 is an encoding in the ISO 8859 family. See also character set and encoding method. 

***encoding method***
    the set of rules that are used for assigning numeric representations to the characters in a character set. For example, these rules specify how many bits are used for storing the numeric representation of the character, as well as the ranges in the code page in which characters appear. The encoding methods are standards that have been developed in the computing industry. An encoding method is often specific to a computer hardware vendor. Common encoding methods include ASCII, EBCDIC, the ISO 646 family, the ISO 8859 family, and Unicode. See also character set and encoding. 

***engine/host option***
    an option that is specified in a LIBNAME statement. Engine/host options specify attributes that apply to all SAS data sets in a SAS library. 

***entry***
    See ODS entry, SAS catalog entry. 

***entry type***
    a characteristic of a SAS catalog entry that identifies the catalog entry's structure and attributes to SAS. When you create a SAS catalog entry, SAS automatically assigns the entry type as part of the name. See also SAS catalog entry. 

***equijoin***
    a kind of join in the SQL procedure. For example, when two tables are joined in an equijoin, the value of a column in the first table must equal the value of the column in the second table in the SQL expression. See also join. 

***exclusion list***
    a list that tells ODS which output objects to exclude from a specified ODS destination. See also selection list.

***executable statement***
    in the DATA step, a SAS statement that causes some action to occur while the DATA step executes rather than when SAS compiles the DATA step. See also declarative statement. 

***execution-time error***
    an error that occurs when SAS executes a step, as opposed to when it compiles a step. 

***Extensible Markup Language***
    a markup language that structures information by tagging it for content, meaning, or use. Structured information contains both content (for example, words or numbers) and an indication of what role the content plays. For example, content in a section heading has a different meaning from content in a database table. Short form: XML. 

***external file***
    a file that is created and maintained by a host operating system or by another vendor's software application. SAS can read data from and route output to external files. External files can contain raw data, SAS programming statements, procedure output, or output that was created by the PUT statement. A SAS data set is not an external file. See also fileref. 

## F

***field***
    in an external file, the smallest logical unit of data. See also file and record.

***file***
    a collection of related records that are treated as a unit. SAS files are processed and controlled by SAS and are stored in SAS libraries. 

***file corruption***
    the result of an operation that changes a file's data or the file's header, causing the file's structure or contents to be inaccessible. A common cause of corruption during file transport is that the transport file contains one or more incorrectly placed carriage returns or line feeds to mark the end of record, which makes the entire file unreadable after it is transferred across a network. Communications software can also cause corruption if it changes file attributes such as logical record length, block size, or record format. 

***file reference***
    See fileref. 

***File Transfer Protocol***
    a TCP/IP-specific telecommunications protocol that is used for transferring files across a network. FTP requires a user to supply a user ID and usually a password in order to access a server. Short form: FTP. 

***fileref***
    a name that is temporarily assigned to an external file or to an aggregate storage location such as a directory or a folder. The fileref identifies the file or the storage location to SAS. See also libref. 

***floating-point representation***
    a compact form of storing real numbers on a computer, similar to scientific notation. Different operating systems use different techniques for floating-point representation. 

***foreign file format***
    a relative term that contrasts the internal data representation of a file with that of an operating environment. If the internal formats are not the same, the file format is considered to be foreign to the operating environment. For example, the format of a file that is created in an OS/390 or z/OS operating environment is considered to be foreign to Windows operating environments. Foreign file formats are also referred to as non-native file formats. See also native file format. 

***foreign key integrity constraint***
    a referential integrity constraint that links the data values of one or more variables in the foreign key data file to corresponding variables and values in the primary key data file. See also integrity constraints, primary key integrity constraint, and referential integrity constraint. 

***form layout***
    the number and arrangement of form units such as mailing labels on a page of continuous-feed paper (a form page). See also form page and form unit. 

***form page***
    a sheet of continuous-feed paper on which form units such as mailing labels are printed. A form page has a line size and a page size associated with it. See also form layout and form unit. 

***form unit***
    the data that is printed in a rectangular block by the FORMS procedure. For example, a mailing label is a form unit. See also alignment form unit, form layout, and form page. 

***format library***
    a collection of user-defined formats and informats. The format library can be a FORMATS catalog in a SAS library, or on z/OS it can also be a load library that contains SAS formats and informats in load module form. See also load library. 

***format modifier***
    a special symbol that is used in the INPUT and PUT statements and which enables you to control how SAS reads input data and writes output data. 

***formatted input***
    a style of input that uses special instructions called informats in the INPUT statement to determine how values that are entered in data fields should be interpreted. See also informat. 

***formatted output***
    a style of output that uses SAS formats in the PUT statement to specify how to write the values of variables. 

***forward compatibility***
    the ability of a SAS client that runs a particular version of SAS to read, write, and update a SAS file that was created using a later version of SAS as long as the SAS file does not implement features such as long names that are specific to the later version. The accessing SAS client and the application that run the earlier version of SAS are said to be forward compatible with the SAS file that was created using the later version. See also backward compatibility. 

***frequency chart***
    a graphic illustration of the number of times a value or range of values occurs for a particular variable. 

***frequency count***
    the number of times a value or range of values occurs for a particular variable. 

***frequency table***
    a table that lists each of the distinct values that a variable has within all of the observations in a SAS data set. For each value, the table also lists the number of observations in which the variable has that value. 

***FTP***
    See File Transfer Protocol. 

***function***
    a component of the SAS programming language that can accept arguments, perform a computation or other operation, and return a value. For example, the ABS function returns the absolute value of a numeric argument. Functions can return either numeric or character results. Some functions are included with SAS. Users can also use SAS/TOOLKIT software to write their own functions. 

***function key***
    a keyboard key that can be defined to have a specific action in a specific software environment. 

***fuzz factor***
    a value that is used when other values are being compared or evaluated in order to offset potential errors that can result from numerical imprecision. If a value does not match or fall within a range exactly but is within the range of the fuzz factor, then the value is considered a match. For example, if an expression evaluates whether a value is greater than or equal to 2.0, and a fuzz factor of .0001 has been specified, then any value that is greater than or equal to 1.9999 would cause the expression to evaluate as true. 

## G

***general integrity constraint***
    an integrity constraint that enables you to restrict the values of variables within a single file. There are four types of general integrity constraints: check, not null, unique, and primary key. See also integrity constraints, primary key integrity constraint, and referential integrity constraint. 

***generation data set***
    an archived version of a SAS data set that is stored as part of a generation data group. A generation data set is created each time the data set is updated. Each generation data set in a generation data group has the same root member name, but each has a different version number. The most recent version is called the base version. 

***generation group***
    a group of data sets that represent a series of replacements to the original data set. The generation group consists of the base version and a set of historical versions. See also base version, generation data set, and historical version. 

***generation number***
    a consistently increasing number that identifies one of the historical versions in a generation group. For example, the data set named AIR#272 has a generation number of 272. See also historical version, generation data set, and generation group. 

***gigabyte***
    a unit of measurement for digital information that is equivalent to one billion bytes. Short form: GB. See also kilobyte, megabyte, and terabyte. 

***global macro variable***
    a macro variable that can be referenced in either global or local scope in a SAS program, except where there is a local macro variable that has the same name. A global macro variable exists until the end of the session or program. See also local macro variable. 

## H

***header***
    1) textual information at the top of either a report, a page, a table, or a table column that identifies or categorizes the information in the report, page, table, or table column. 2) part of an Internet protocol message, such as a MIME message or an HTTP message, that provides information about the message. Headers are created by Internet applications and are used to identify users and to debug Internet message problems. 

***header routine***
    a group of DATA step statements that produces page headers in print files. A header routine begins with a statement label and ends with a RETURN statement. You identify with the HEADER= option in the FILE statement. 

***historical version***
    an older copy of the base version of a data set. Names of historical versions include a four-character suffix for the generation number, such as #003. See also base version, generation data set, and generation group. 

***holidays data set***
    in the CALENDAR procedure, a SAS data set that specifies which holidays to display in a summary calendar or in a schedule calendar. See also schedule calendar and summary calendar. 

***host***
    See host operating environment. 

***host operating environment***
    the operating environment (computer, operating system, and other software and hardware) that provides centralized control for software applications. 

***HTML***
    See HyperText Markup Language. 

***HyperText Markup Language***
    a coding system in which the codes indicate the layout and style of the text in a text file. Other HTML codes enable you to embed electronic objects such as images, sounds, video streams, and applets (small software applications) into HTML documents. All Web browsers can process HTML documents. Short form: HTML.

## I

***I/O-bound application***
    an application whose performance is constrained by the speed at which data can be delivered for processing. Multiple CPUs, partitioned I/O, threading technology, RAID (redundant array of independent disks) technology, or a combination of these can alleviate this problem. 

***icon***
    in windowing environments, a pictorial representation of an object. An icon usually represents an application window or is associated with an action such as printing or filing. 

***importing transport files***
    the process of returning SAS transport files to their original form (SAS library, SAS catalog, or SAS data set) in a format that is appropriate for the target operating environment. The terms 'import' and 'restore' can both be used to describe this process, but 'import' usually refers to the use of the CIMPORT procedure. See also restoring transport files. 

***incompatible operating environments***
    See architectural compatibility. 

***infix operator***
    a symbol that specifies an operation that is applied to two operands, one on each side (for example, the greater-than symbol in 8 > 6 or the plus sign in A + B). There are four general kinds of infix operators: arithmetic, comparison, logical (Boolean), and others (minimum, maximum, and concatenation). 

***informat***
    a pattern or set of instructions that SAS uses to determine how data values in an input file should be interpreted. SAS provides a set of standard informats and also enables you to define your own informats. 

***in-line view***
    a query-expression that is nested in the SQL procedure's FROM clause. An in-line view produces a table internally that the outer query uses to select data. You save a programming step when you use an in-line view, because instead of creating a view and then referring to it in another query, you can specify the view in-line in the FROM clause. An in-line view can be referenced only in the query (or statement) in which it is defined. See also query-expression. 

***inner join***
    See join. 

***input buffer***
    a temporary area of memory into which each record of data is read when the INPUT statement executes. 

***input stack***
    the most recently read line of input from a SAS program and any text generated by the macro processor that is awaiting processing by the word scanner. See also word scanner. 

***input/output operation***
    any operation of physically reading data from a storage medium, such as a disk or tape, or writing data to a storage medium. 

***integer arithmetic***
    arithmetic that uses only integers (numbers that do not contain a decimal point) and that produces only integers as a result. 

***integrity constraints***
    a set of data validation rules that you can specify in order to restrict the data values that can be stored for a variable in a SAS data file. Integrity constraints help you preserve the validity and consistency of your data. There are two types of integrity constraints: general and referential. See also general integrity constraint and referential integrity constraint. 

***interactive line mode***
    a method of running SAS programs without using the SAS windowing environment. You enter one line of a SAS program at a time, and SAS processes each line immediately after you enter it. Procedure output and informative messages are returned directly to your display device. 

***interface library engine***
    a SAS library engine that accesses files that have been formatted by another vendor's software. For example, interface library engines are used to access SPSS, OSIRIS, and BMDP data. An interface view engine is a particular type of interface library engine that is used by SAS/ACCESS software. See also interface view engine and native library engine. 

***interface view***
    a SAS data view that is created with SAS/ACCESS software. An interface view describes data that is stored in a database management system (DBMS) or a PC data file. Interface views are used as input to DATA steps and procedures. With certain restrictions, an interface view can be used to update data. Interface views are also referred to as SAS/ACCESS views. In order to use SAS/ACCESS views, you must have a license for SAS/ACCESS software. See also view descriptor and SAS/ACCESS view. 

***interface view engine***
    a type of SAS interface library engine that SAS/ACCESS software uses to retrieve data from files that have been formatted by another vendor's software. Each SAS/ACCESS interface has its own interface view engine, which reads the interface product data and returns the data in a form that SAS can understand (that is, in a SAS data set). See also interface library engine. 

International Organization for Standardization***
    an organization that promotes the development of standards and that sponsors related activities in order to facilitate the dissemination of products and services among nations and to support the exchange of intellectual, scientific, and technological information. Short form: ISO. 

***internationalization***
    the process of designing a software application without making assumptions that are based on a single language or locale. See also national language support. 

***interquartile range***
    the difference between the third quartile, or 75th percentile, and the first quartile, or 25th percentile. Short form: IQR. 

***IQR***
    See interquartile range. 

***ISO***
    See International Organization for Standardization. 

***ISO 646 family***
    a group of 7-bit encodings that are defined in the ISO 646 standard and that each include 128 characters. The ISO 646 encodings are similar to ASCII except for 12 code points that are used for national variants. National variants are specific characters that are needed for a particular language. 

***ISO 8859 family***
    a group of 8-bit extensions to ASCII that support all 128 of the ASCII code points plus an additional 128 code points, for a total of 256 characters. ISO-8859-1 (Latin 1) is a commonly used member of the ISO 8859 family of encodings. In addition to the ASCII characters, ISO-8859-1 contains accented characters, other letters that are needed for languages of Western Europe, and some special characters. 

***item store***
    a SAS data set that consists of pieces of information that can be accessed independently. The contents of an item store are organized in a directory tree structure, which is similar to the directory structures that are used by UNIX System Services or by Windows. For example, a particular value might be stored and located using a directory path (root_dir/sub_dir/value). The SAS Registry is an example of an item store. See also template store. 

## J

***job stream***
    a series of related programs that are run in a prescribed order. 

***join***
    in the SQL procedure, the combination of data from two or more tables (or from two or more SAS data views) to produce a single result table. A conventional join, which is often called an inner join, returns a result table for all the rows in one table that have one or more matching rows in the other table or tables. See also outer join. 

***join criteria***
    the set of parameters that determine how tables are to be joined. Join criteria are usually specified in a WHERE expression or in an SQL ON clause. See also join and outer join. 

## K

***key variable***
    (1) a variable that is used to index SAS data sets. (2) in table lookup applications, a variable that resides in both the primary file and the lookup file. The values of the key variable are the common elements between the files. Typically, key values are unique in the lookup file but are not necessarily unique in the primary file. 

***KEYS entry***
    a type of SAS catalog entry that contains function key settings for interactive windowing procedures. 

***kilobyte***
    2 to the 10th power, or 1024 bytes. See also gigabyte, megabyte, and terabyte.

***kurtosis***
    a measure of the "heaviness of the tails" of a distribution relative to the normal distribution, which has a kurtosis of zero. 

## L

***label, variable***
    up to 256 characters of descriptive text that can be printed in the output by certain procedures instead of, or in addition to, the variable name. 

***language***
    an aspect of locale that is not necessarily unique to any one country or geographic region. For example, Portuguese is spoken in Brazil as well as in Portugal, but there are separate locales for Portuguese_Portugal and Portuguese_Brazil. See also locale. 

***length variable***
    a numeric variable that is used with the $VARYING. informat or format to specify the actual length of a character variable whose values do not all have the same length. 

***length, variable***
    the number of bytes used to store each of a variable's values in a SAS data set. 

***library engine***
    an engine that accesses groups of files and puts them into the correct form for processing by SAS utility windows and procedures. A library engine also determines the fundamental processing characteristics of the library, presents lists of files for the library directory, and supports view engines. There are two types of library engines: native library engines and interface library engines. See also interface library engine, and native library engine. 

***library reference***
    See libref. 

***libref***
    a name that is temporarily associated with a SAS library. The complete name of a SAS file consists of two words, separated by a period. The libref, which is the first word, indicates the library. The second word is the name of the specific SAS file. For example, in VLIB.NEWBDAY, the libref VLIB tells SAS which library contains the file NEWBDAY. You assign a libref with a LIBNAME statement or with an operating system command. 

***light-weight process thread***
    a single-threaded subprocess that is created and controlled independently, usually with operating system calls. Multiple light-weight process threads can be active at one time on symmetric multiprocessing (SMP) hardware or in thread-enabled operating systems. 

***line mode***
    See interactive line mode. 

***line-hold specifier***
    a special symbol used in INPUT and PUT statements that enables you to hold a record in the input or output buffer for further processing. Line-hold specifiers include the trailing at sign (@) and the double trailing at sign (@@). 

***list input***
    a style of input in which names of variables, not column locations, are specified in the INPUT statement. List input scans input records for data values that are separated by at least one blank or by some other delimiter. 

***list output***
    a style of output in which character strings or variables are specified in a PUT statement without explicit directions that specify where SAS should place the strings or values. 

***LISTING destination***
    an ODS destination that produces traditional SAS output (monospace format). See also list output and ODS destination.

***little endian***
    a term that is used to describe the order in which a sequence of bytes is stored in computer memory (byte ordering). On little endian platforms, the value 1 is stored in one byte as 01 (the same as on big endian platforms), in two bytes as 01 00, and in four bytes as 01 00 00 00. The least significant value in the sequence is stored last. In the SAS System, the following platforms are considered little endian: OpenVMS Alpha, Digital UNIX, Intel ABI, and Windows. See also big endian. 

***load library***
    an external file that contains load modules. These can be modules that are supplied by SAS, or they could be compiled and linked by other sources. See also format library and load module. 

***load module***
    a complete machine-level program in a form that is ready to be loaded into main memory and executed. 

***local macro variable***
    a macro variable that is available only within the macro in which it was created and within macros that are invoked from within that macro. A local macro variable ceases to exist when the macro that created it stops executing. See also global macro variable. 

***locale***
    a value that reflects the language, local conventions, and culture for a geographic region. Local conventions can include specific formatting rules for dates, times, and numbers, and a currency symbol for the country or region. Collating sequences, paper sizes, and conventions for postal addresses and telephone numbers are also typically specified for each locale. Some examples of locale values are French_Canada, Portuguese_Brazil, and English_USA. 

***localization***
    the process of adapting a product to meet the language, cultural, and other requirements of a specific target environment or market so that customers can use their own languages and conventions when using the product. Translation of the user interface, system messages, and documentation is part of localization. 

***log***
    See SAS log. 

***logical data model***
    a framework into which engines fit information for processing by SAS. This data model is a logical representation of data or files, not a physical structure. 

***logical name***
    a name that is assigned to or associated with a file specification, a directory path, a device name or another logical name. In SAS software, logical names can be assigned by using the LIBNAME, FILENAME, or CATNAME statement. Some logical names can be assigned with commands that are specific to an operating environment. See also catref, fileref, and libref. 

***logical operator***
    an operator that is used in expressions to link sequences of comparisons. The logical operators are AND, OR, and NOT. 

***logical page***
    in the TABULATE procedure, all of the rows and columns that are defined by a TABLE statement. A logical page can contain more rows and columns than can fit on one physical page. If the logical page has to be broken into parts, then each part is printed on a separate physical page. When the logical pages are short, you can print several of them on one page by using the CONDENSE option. 

***logical record length***
    the number of bytes in a unit of information that consists of related data such as a line in an external file or a SAS observation. Default values for the logical record lengths depend on the operating environment. 

***lookup file***
    an auxiliary file that is maintained separately from the primary file and that is referenced for one or more of the observations of the primary file. A set of SAS statements can provide values that serve as the lookup file. The values of format tables also serve as lookup files. See also primary file. 

***lookup result***
    in table lookup applications, the auxiliary information obtained using the key or keys as a reference into the lookup file. 

***lookup table***
    See automatic lookup table. 
    
## M

***macro***
    a SAS catalog entry that contains a group of compiled program statements and stored text. 

***macro compilation***
    the process of converting a macro definition from the statements that you enter to a form that is ready for the macro processor to execute. The compiled macro is then stored for later use in the SAS program or session. 

***macro execution***
    the process of following the instructions that are given by compiled macro program statements in order to generate text, to write messages to the SAS log, to accept input, to create or change the values of macro variables, or to perform other activities. The generated text can be a SAS statement, a SAS command, or another macro program statement. 

***macro expression***
    any valid combination of symbols that returns a value when it is executed. The three types of macro expressions are text, logical, and arithmetic. A text expression generates text when it is resolved (executed) and can consist of any combination of text, macro variables, macro functions, and macro calls. A logical expression consists of logical operators and operands and returns a value of either true or false. An arithmetic expression consists of arithmetic operators and operands and returns a numeric value. 

***macro facility***
    a component of Base SAS software that you can use for extending and customizing SAS programs and for reducing the amount of text that must be entered in order to perform common tasks. The macro facility consists of the macro processor and the macro programming language. 

***macro function***
    a function that is defined by the macro facility. Each macro function processes one or more arguments and produces a result. 

***macro language***
    the programming language that is used to communicate with the macro processor. 

***macro processor***
    the component of SAS software that compiles and executes macros and macro program statements. 

***macro quoting***
    a function that tells the macro processor to interpret special characters and mnemonics as text rather than as part of the macro language. See also quoting. 

***macro variable***
    a variable that is part of the SAS macro programming language. The value of a macro variable is a string that remains constant until you change it. Macro variables are sometimes referred to as symbolic variables. 

***main memory***
    an area that a central processing unit (CPU) can access rapidly and from which it executes instructions and operates on data. 

***markup language***
    a set of codes that are embedded in text in order to define layout and certain content. 

***master data set***
    in an update operation, the data set that contains the information that you want to update. See also transaction data set.

***matching observations***
    in the COMPARE procedure, observations that have the same values for all ID variables that you specify. If you do not use the ID statement, then matching observations are observations that occur in the same position in the data sets that are being compared. 

***matching variables***
    in the COMPARE procedure, variables that have the same name, or variables that you explicitly pair by using the VAR and WITH statements. 

***match-merging***
    a process in which SAS joins observations from two or more SAS data sets according to the values of the BY variables. See also one-to-one merging. 

***MDDB***
    See multidimensional database. 

***megabyte***
    2 to the 20th power, or 1,048,576 (approximately 1 million) bytes. See also gigabyte, kilobyte, and terabyte.

***member***
    a SAS file in a SAS library. Under z/OS, this term can also refer to a single member of a partitioned data set. Under OpenVMS, it can refer to a component of an OpenVMS text library. 

***member name***
    a name that is assigned to a SAS file in a SAS library. See also member type.

***member type***
    a SAS name that identifies the type of information that is stored in a SAS file. Member types include ACCESS, AUDIT, DMBD, DATA, CATALOG, FDB, INDEX, ITEMSTOR, MDDB, PROGRAM, UTILITY, and VIEW. 

***memory***
    an area into which a computer can copy a unit of information that will hold the information and from which the computer can obtain the information at a later time. 

***menu***
    a window object that presents choices to users. In SAS software, menus include menu bars, pull-down menus, block menus, and selection lists. 

***menu bar***
    a list of selections that appear when the PMENU command is executed. 

***merging***
    the process of combining observations from two or more SAS data sets into a single observation in a new SAS data set. See also one-to-one merging. 

***message area***
    the area immediately beneath a window's command line or menu bar which displays messages from SAS or from the SAS Component Language reserved variable _MSG_. 

***metadata***
    a description or definition of data or information. 

***metadata LIBNAME engine***
    the SAS engine that processes and augments data that is identified by metadata. The metadata engine retrieves information about a target SAS data library from metadata objects in a specified metadata repository. 

***metadata object***
    a set of attributes that describe a table, a server, a user, or another resource on a network. The specific attributes that a metadata object includes vary depending on which metadata model is being used. 

***metadata repository***
    a collection of related metadata objects, such as the metadata for a set of tables and columns that are maintained by an application. A SAS Metadata Repository is an example. 

***metadata server***
    a server that provides metadata management services to one or more client applications. A SAS Metadata Server is an example. 

***missing value***
    in SAS, a term that describes the contents of a variable that contains no data for a particular row or observation. By default, SAS prints or displays a missing numeric value as a single period, and it prints or displays a missing character value as a blank space. 

***mnemonic operator***
    an arithmetic or logical (Boolean) operator that consists of letters rather than symbols (for example, EQ rather than =). 

***mode***
    the most frequent value of a variable. 

***mode of execution***
    a method of executing or interacting with SAS software, which can include noninteractive mode, batch mode, interactive mode (using the SAS windowing environment or other graphical user interfaces), and interactive line mode. 

***modified list input***
    a style of input that uses special instructions called informats and format modifiers in the INPUT statement. Modified list input scans input records for data values that are separated by at least one blank (or by some other delimiter), or in some cases, by multiple blanks. 

***moving average***
    an average of a specified number of consecutive values that move according to the current observation. 

***moving SAS files***
    the process of passing SAS files from one operating environment to another operating environment, either by means of magnetic media or across a network. Three specific variations of moving a SAS file are converting, copying, and transporting. See also converting SAS files, copying SAS files, and transporting SAS files. 

***multidimensional array***
    a grouping of variables of the same data type under a single name, with at least two dimensions. When processed, this grouping of variables produces results in columns, rows, and, depending on the array, higher dimensions. See also one-dimensional array and two-dimensional array. 

***multidimensional database***
    a specialized data storage structure in which data is presummarized and cross-tabulated and then stored as individual cells in a matrix format, rather than in the row-and-column format of relational database tables. The source data can come either from a data warehouse or from other data sources. MDDBs can give users quick, unlimited views of multiple relationships in large quantities of summarized data. Short form: MDDB. 

***multi-panel report***
    output that uses sets of columns on a page to display the values of variables. For example, telephone books are usually arranged in multiple panels of names, addresses, and telephone numbers on a single page. 

***multitasking***
    the ability of an operating system to execute more than one application (or multiple instances of the same application) at the same time, using a single central processing unit. Individual tasks within the applications are scheduled so that the applications appear to be running at the same time and so that the applications do not interfere with each other. Almost all operating systems are capable of multitasking. 

***multi-threading***
    See threading.

## N

***name-style macro***
    a macro that is named and defined with the %MACRO statement. See also command-style macro and statement-style macro.

***naming conventions, SAS***
    the rules that describe what constitutes a valid name for SAS variables, data sets, librefs, filerefs, and other constructs of the SAS programming language. See also SAS name. 

***national character***
    any character that is specific to a language as it is written in a particular nation or group of nations. 

***national language support***
    the set of features that enable a software product to function properly in every global market for which the product is targeted. Short form: NLS. 

***native file format***
    a relative term that compares the internal data representation of a file with that of an operating environment. If the internal formats are the same, the file format is considered to be native to the operating environment. For example, the format of a file that is created in a Windows operating environment is considered to be native to Windows operating environments. See also foreign file format. 

***native library engine***
    a SAS engine that accesses types of SAS files that are created and processed only by SAS. See also interface library engine. 

***native view***
    a SAS data view that is created either with a DATA step or with PROC SQL. 

***natural join***
    a type of join that returns selected rows from tables in which one or more columns in each table have the same name and the same data type and contain the same value. See also join. 

***nibble***
    half a byte, or 4 bits (binary digits). 

***NLS***
    See national language support. 

***noninteractive mode***
    a method of running SAS programs in which you prepare a file of SAS statements and submit the program to the operating system. The program runs immediately and comprises your current session. 

***noninteractive processing***
    See noninteractive mode. 

***normal probability plot***
    a plot that compares the distribution of input data with the normal distribution. In the UNIVARIATE procedure, asterisks (*) represent the input data, and plus signs (+) form the reference line. 

***null statement***
    a statement that consists of a single semicolon or four semicolons. The null statement is most commonly used to designate the end of instream data in a DATA step. 

***null value***
    in the SAS macro language, a value that consists of zero characters. 

***numeric constant***
    a number that appears in a SAS expression. 

***numeric format***
    a set of instructions that tell SAS to use a specific pattern for writing the values of numeric variables. 

***numeric informat***
    a set of instructions that tell SAS to use a specific pattern for reading numeric data values. 

***numeric value***
    a value that usually contains only numbers, which can include numbers in E-notation and hexadecimal notation. A numeric value can sometimes contain a decimal point, a plus sign, or a minus sign. Numeric values are stored in numeric variables. 

***numeric variable***
    a variable that contains only numeric values and related symbols, such as decimal points, plus signs, and minus signs. By default, SAS stores all numeric variables in floating-point representation. 

## O

***observation***
    a row in a SAS data set. All of the data values in an observation are associated with a single entity such as a customer or a state. Each observation contains either one data value or a missing-value indicator for each variable. 

***ODS***
    See Output Delivery System. 

***ODS destination***
    a designation that the Output Delivery System uses to generate a specific type of output. Types of ODS destinations include but are not limited to HTML, XML, listing, Postscript, RTF, and SAS data sets. 

***ODS entry***
    an item in an ODS document. An ODS entry can be either a link, an output object, a file, or a partitioned data set. 

***ODS event***
    within a tagset definition, an action that causes output to be generated. Events are usually triggered by SAS but can also be triggered by other events. 

***ODS markup family***
    a group of ODS statements that produce SAS output that is formatted using a markup language such as HTML (HyperText Markup Language), XML (Extensible Markup Language), and LaTeX. SAS supplies many markup languages for you to use, ranging from DOCBOOK to TROFF. You can specify a markup language that SAS supplies, or you can create one of your own and store it as a user-defined markup language. See also ODS destination and ODS printer family. 

***ODS output***
    formatted output that is generated by any of the ODS destinations. For example, the OUTPUT destination produces SAS data sets, the LISTING destination produces listing output, and the HTML destination produces output that is formatted in Hypertext Markup Language. 

***ODS printer family***
    a group of ODS statements that produce output in a format such as PostScript (PS), PDF, or PCL that is suitable for printing on a high-resolution printer. 

***ODS-5***
    See On-Disk Structure Level 5. 

***oldest version***
    the oldest historical version of a data set in a generation group. See also generation group.

***On-Disk Structure Level 5***
    a file system structure that is implemented by OpenVMS Alpha for Itanium servers. ODS-5 allows longer filenames, supports more legal characters within filenames, preserves case within filenames, supports deeper directory structures, and provides better compatibility with other file systems such as those used with UNIX or Windows. Short form: ODS-5. 

***one-dimensional array***
    a grouping of variables of the same type under a single name. When processed, this grouping of variables produces results that can be presented in simple column format. See also multidimensional array and two-dimensional array. 

***one-to-one matching***
    the process of combining observations from two or more data sets into one observation, using two or more SET statements to read observations independently from each data set. See also match-merging. 

***one-to-one merging***
    the process of using the MERGE statement (without a BY statement) to combine observations from two or more data sets based on the observations' positions in the data sets. See also match-merging. 

***open code***
    the part of a SAS program that is outside any macro definition. 

***operand***
    any of the variables and constants in a SAS expression that contain operators, variables, and constants. 

***operating environment***
    a computer, or a logical partition of a computer, and the resources (such as an operating system and other software and hardware) that are available to the computer or partition. 

***operating system data set***
    a collection of information that IBM mainframe operating systems such as z/OS and OS/390 can identify and manage as a unit. IBM operating system data sets correspond to files under other operating systems. Partitioned data sets (PDSs), sequential data sets, and VSAM data sets are some types of data sets that are supported in IBM mainframe environments. By contrast, SAS data sets are managed by SAS software, not by any operating system, although they can be stored as members of partitioned data sets or in sequential data sets on IBM mainframes. 

***operator***
    (1) in a SAS expression, any of several symbols that request a comparison, a logical operation, or an arithmetic calculation. (2) in the TABULATE procedure, any of several symbols that indicate relationships between elements of a dimension expression. PROC TABULATE provides operators for crossing, concatenating, and grouping elements, as well as an operator for assigning labels. 

***order variable***
    in the REPORT procedure, a variable that orders the detail rows in a report according to their formatted values. A report that contains one or more order variables has a detail row for every observation in the data set. 

***OSIRIS engine***
    the SAS engine that provides read-only access to OSIRIS data files and dictionary files. 

***outer join***
    in the SQL procedure, an inner join that is augmented with rows that do not match any row from the other table or tables in the join. There are three kinds of outer joins: left, right, and full. See also join. 

***output buffer***
    in the DATA step, the area of memory that a PUT statement writes to before it writes to a designated file or output device. 

***Output Delivery System***
    a component of SAS software that can produce output in a variety of formats such as markup languages (HTML, XML), PDF, listing, RTF, PostScript, and SAS data sets. Short form: ODS. 

***output object***
    a programming object that contains the data that is generated by a DATA step or a PROC step and which can also contain a table definition that provides information about how to format that data. 

***overhead***
    in benchmarking, the additional resources that are used to move a component of SAS software (such as a procedure) into main memory the first time a program uses that component. 

***overprint character***
    the character that is printed when two or more plotting symbols have the same print position. In most procedures, the default overprint character is the at sign (@). 

## P

***packed decimal data***
    a method of encoding decimal numbers in which each byte represents two decimal digits. See also zoned decimal data.

***padding a value with blanks***
    in SAS software, a process in which the software adds blanks to the end of a character value that is shorter than the length of the variable. 

***page dimension***
    in the TABULATE procedure, the combination of variables, variable values, and statistics that determine the number and arrangement of pages in the table. See also dimension and dimension expression. 

***page expression***
    in the TABULATE procedure, the part of the TABLE statement that determines the content and appearance of the page dimension by specifying the combination of variables, variable values, and statistics that make up that dimension. See also column expression and row expression. 

***page size***
    the number of bytes of data that SAS moves between external storage and memory in one input/output operation. Page size is analogous to buffer size for SAS data sets. 

***panel***
    each set of columns in a multi-panel report. See also multi-panel report.

***parallel I/O***
    a method of input and output that takes advantage of multiple CPUs and multiple controllers, with multiple disks per controller to read or write data in independent threads. 

***parallel processing***
    a method of processing that uses multiple CPUs to process independent threads of an application’s computations. See also threading.

***parameter***
    (1) a characteristic for which a user supplies a specific value, usually either by choosing or entering the value via a graphical user interface, or by specifying the value as part of the syntax of a programming-language element such as a SAS function, statement, command, or procedure. For example, user names, passwords, font specifications, and the type of chart or graph that you want a program to generate could all be considered parameters. Parameters can also be passed from one program or application to another. (2) in the SAS macro facility, a local macro variable that is defined within parentheses in a %MACRO statement. You supply values to a macro parameter when you invoke a macro. 

***partition***
    in the SAS Scalable Performance Data Engine, part or all of a logical file that spans devices or directories. A partition is one physical file. Data files, index files, and metadata files can all be partitioned, resulting in data partitions, index partitions, and metadata partitions, respectively. Partitioning a file can improve performance for very large data sets. See also data partition and partitioned data set. 

***partitioned data set***
    (1) in IBM mainframe environments such as z/OS and OS/390, a type of operating system data set that consists of one or more separate units of information called members, plus a directory. For each member, a unique name is entered in the PDS directory. Partitioned data sets must reside on disk. (2) in the SAS Scalable Performance Data Engine, a type of SAS data set whose data is stored in multiple physical files (partitions) so that it can span storage devices. One or more partitions can be read in parallel by using threads. This improves the speed of I/O and processing for very large data sets. See also operating system data set. 

***password***
    in SAS software, a valid SAS name that a user must correctly specify in order to gain access to SAS files. Passwords can grant read, write, or alter access. 

***paste buffer***
    a temporary storage location that holds text that is stored with the STORE or CUT command. The contents of the paste buffer remain in effect only for the current SAS session. 

***PCL***
    See Printer Command Language. 

***PCTN***
    a statistic that provides the percentage of the frequency in a single cell to a total frequency. The total frequency that is used for computing the percentage is defined by the denominator definition that follows the PCTN statistic. 

***PCTSUM***
    a statistic that provides the percentage of the sum in a single cell to another total. The total that is used for computing the percentage is defined by the denominator definition that follows the PCTSUM statistic. This statistic can be requested only for analysis variables. 

***PDS***
    See partitioned data set. 

***PDV***
    See program data vector. 

***percentile***
    a value that is larger than a particular percentage of the values of a variable. For example, the 95th percentile is larger than 95 percent of the values of the variable. 

***performance statistics***
    data that contains measurements of the amount of resources a program uses when it is compiled and executed. 

***permanent SAS data set***
    a SAS data set that is not deleted after the current program or interactive SAS session ends. Permanent SAS data sets are available for future SAS sessions. 

***permanent SAS file***
    a file in a SAS library that is not deleted when the SAS session or job terminates. 

***PF key***
    See function key.

***physical filename***
    the name that an operating system uses to identify a file. 

***physical order***
    in SAS software, the order in which observations appear in their storage structure. 

***physical page***
    in the TABULATE procedure, the portion of a table that is formatted to print on a single sheet of paper or a single display. A physical page and a logical page may be the same, or a physical page may not contain the entire logical page, or it may contain several logical pages if the CONDENSE option is specified. 

***picture***
    in the FORMAT procedure, a template for printing the values of numeric variables. 

***picture format***
    in the FORMAT procedure, a user-defined format for displaying numeric values. Picture formats are defined with the PICTURE statement. 

***platform***
    the operating environment in which a program runs, which includes both the operating system and the computer hardware. 

***plotting symbol***
    a character that is used to plot the values of plotting variables. By default, the TIMEPLOT procedure uses the first character of the variable name as the plotting symbol. 

***plotting variables***
    the variables that you specify in a PLOT statement. Plotting variables must be numeric. 

***PMENU entry***
    a type of catalog entry that contains definitions for pull-down menus, menu bars, and dialog boxes created by the PMENU procedure. 

***PMENU facility***
    a menu system in SAS that is used instead of the command line as a way to execute commands. The PMENU facility consists of a menu bar, pull-down menus, and ***dialog boxes. 

***pointer***
    in the DATA step, a programming tool that SAS uses to keep track of its position in the input or output buffer. 

***pointer control***
    the process of instructing SAS to move the pointer before reading or writing data. 

***pop-up menu***
    a menu that appears when it is requested. These menus are context-specific, depending on which window is active and on the cursor location. See also pull-down menu. 

***portability***
    the ability of a program to execute in an operating environment other than the one for which it was written. 

***positional parameter***
    in the macro facility, a parameter that is defined by name only. The parameter's value is assigned by matching the parameter (which is in a particular position in the %MACRO statement) with the value that is in the corresponding position (delimited by commas) in the macro invocation. 

***precision***
    See data precision. 

***primary file***
    in table lookup applications, the file for which you want to obtain auxiliary information. See also lookup file.

***primary key integrity constraint***
    a type of general integrity constraint that requires that the specified variable(s) contain unique data values and which does not allow null data values. A data file can contain only one primary key. If the primary key integrity constraint in one data file is referenced by a foreign key integrity constraint in another file, then the primary key integrity constraint is a referential integrity constraint. See also integrity constraints, general integrity constraint, and referential integrity constraint. 

***primary path***
    the location in which SPD Engine metadata files are stored. The other SPD Engine component files (data files and index files) are stored in separate storage paths in order to take advantage of the performance boost of multiple CPUs. 

***print file***
    an external file that contains carriage-control (printer-control) information. See also carriage-control character and external file. 

***Printer Command Language***
    a command language that was developed by Hewlett-Packard for controlling Hewlett-Packard printers. Each PCL command consists of an escape key followed by a series of code numbers. Different versions of PCL have been developed for use with different models or types of Hewlett-Packard printers. Short form: PCL. 

***PROC SQL view***
    a SAS data set that is created by the SQL procedure. A PROC SQL view contains no data. Instead, it stores information that enables it to read data values from other files, which can include SAS data files, SAS/ACCESS views, DATA step views, or other PROC SQL views. The output of a PROC SQL view can be either a subset or a superset of one or more files. See also SAS data view. 

***PROC step***
    a group of SAS statements that call and execute a SAS procedure. A PROC step usually takes a SAS data set as input. 

***procedure***
    See SAS procedure. 

***procedure output file***
    an external file that contains the result of the analysis that a SAS procedure performs or the report that the procedure produces. Most SAS procedures write output to the procedure output file by default. Reports that are produced by SAS DATA steps, using PUT statements and a FILE statement along with a PRINT destination, also go to this file. See also external file and DATA step. 

***process***
    a functional unit of a program or task. In a thread-enabled operating system, a process can consist of a single thread, or it can contain many threads that collectively perform a complex function. See also thread and thread-enabled operating system. 

***Profile catalog***
    See Sasuser.Profile catalog. 

***program compilation***
    See compilation. 

***program data vector***
    the temporary area of computer memory in which SAS builds a SAS data set, one observation at a time. The program data vector is a logical concept and does not necessarily correspond to a single contiguous area of memory. Short form: PDV. 

***programming error***
    a flaw in the logic of a SAS program that can cause the program to fail or to perform differently than the programmer intended. See also data error and syntax error. 

***PROMPT facility***
    in the REPORT procedure, a tool that is implemented through the PROMPTER window. The facility prompts you for information as you add either data set variables or statistics to a report. It steps you through the most commonly used parts of the windows that you would use to add the variables to a report if you were not using the PROMPT facility. The PROMPTER window provides more guidance than the other windows provide. 

***propagation of missing values***
    a consequence of using missing values in which a missing value in an arithmetic expression causes SAS to set the result of the expression to missing. Using that result in another expression causes the next result to be missing, and so on. 

***pull-down menu***
    the list of menu items or choices that appears when you choose an item from a menu bar or from another menu. See also PMENU facility and pop-up menu. 

## Q

***quantile***
    any of the points or values that divide data into groups that contain equal numbers of observations, or any of those groups. Quartiles, quintiles, and percentiles are all examples of quantiles. 

***query***
    a set of instructions that requests particular information from one or more data sources. 

***query-expression***
    in PROC SQL, one or more table-expressions that can be linked with set operators. The primary purpose of a query-expression is to retrieve data from tables, PROC SQL views, or SAS/ACCESS views. In PROC SQL, the SELECT statement is contained in a query-expression. 

***quintile***
    any of the four points that divide the values of a variable into five groups of equal frequency, or any of those groups. 

***quoting***
    the process that causes the macro processor to read certain items as text rather than as symbols in the macro language. Quoting is also called removing the significance of an item and treating an item as text. 

***quoting function***
    a macro language function that performs quoting on its argument. 

## R

***RAID***
    See redundant array of independent disks. 

***random access***
    in the SAS data model, a pattern of access by which SAS processes observations according to the value of some indicator variable without processing all observations sequentially. 

***range***
    All the values that a variable has in a particular data set, from the lowest to the highest. In a frequency distribution, the difference between the largest and smallest values of a variable. 

***ranking***
    the process of ordering observations according to values of particular variables. 

***raw data***
    (1) data that has not been read into a SAS data set. (2) in statistical analysis, data (including data in SAS data sets) that has not had a particular operation, such as standardization, performed on it. See also raw data file. 

***raw data file***
    an external file whose records contain data values in fields. A DATA step can read a raw data file by using the INFILE and INPUT statements. 

***record***
    a logical unit of information that consists of fields of related data. A collection of records are stored in a file. A record is analogous to a SAS observation. 

***recursive execution***
    in the macro facility, a process that occurs when a macro invokes itself or when it invokes another macro that invokes the original macro. 

***redundancy***
    a characteristic of computing systems in which multiple interchangeable components are provided in order to minimize the effects of failures, errors, or both. For example, if data is stored redundantly (in a RAID, for example), then if one disk is lost, the data is still available on another disk. See also redundant array of independent disks. 

***redundant array of independent disks***
    a type of storage system that comprises many disks and which implements interleaved storage techniques that were developed at the University of California at Berkeley. RAIDs can have several levels. For example, a level-0 RAID combines two or more hard drives into one logical disk drive. Various RAID levels provide various levels of redundancy and storage capability. A RAID provides large amounts of data storage inexpensively. Also, because the same data is stored in different places, I/O operations can overlap, which can result in improved performance. Short form: RAID. See also redundancy. 

***reference lines***
    the vertical lines on a plot that indicate whether the values of plotting variables are less than, greater than, or equal to a particular value. 

***referential integrity constraint***
    an integrity constraint that is created when a primary key integrity constraint in one data file is referenced by a foreign key integrity constraint in another data file. The foreign key integrity constraint links the data values of one or more variables in the foreign key data file to corresponding variables and values in the primary key data file. See also integrity constraints, foreign key integrity constraint, general integrity constraint, and primary key integrity contraint. 

***regressing SAS files***
    the process of moving SAS files from a particular version of SAS to an earlier version -- for example, from SAS 9 to SAS 6.12. If the files created in the later version contain features such as integrity constraints that are not supported in the earlier version, then you cannot regress the files. Instead, you re-create the files in an operating environment that runs the later version of SAS. 

***relational database management system***
    a database management system that organizes and accesses data according to relationships between data items. The main characteristic of a relational database management system is the two-dimensional table. Examples of relational database management systems are DB2, Oracle, SYBASE, and Microsoft SQL Server. 

***report break***
    in the REPORT procedure, a break at the beginning or end of a report. See also break.

***report variable***
    in the REPORT procedure, a variable that constitutes one or more columns of the report. The variable might or might not appear in one or more code segments. You can suppress the display of a report variable with the NOPRINT option or the NOZERO option in the DEFINITION window or in the DEFINE statement. 

***reserved word***
    a name that is reserved for use by an internal component of a software application and which therefore cannot be assigned by a user of that application to any type of data object. 

***resource***
    in system performance, a part of the computer system, such as memory or CPU time. 

***Resource Measurement Facility***
    a feature of the z/OS and OS/390 operating systems that records information about each job that is processed. Short form: RMF. 

***restoring transport files***
    the process of returning SAS transport files to their original form (SAS library, SAS catalog, or SAS data set) in the format that is appropriate to the target operating environment. Restoration is performed using either of two techniques, as appropriate: 1) the COPY procedure to restore a SAS transport file that was created by the COPY procedure with the XPORT engine, 2) the CIMPORT procedure to restore a SAS transport file that was created by the CPORT procedure. Restoring is also referred to as reading or importing transport files. See also importing transport files. 

***return code***
    a code that is passed to the operating system and that indicates whether a command or a job step has executed successfully. 

***returned value***
    a value that is the result of the execution of a function. 

***RMF***
    See Resource Measurement Facility. 

root file location***
    the top level of a file location in an ODS document. A root file location is not contained within another file location and does not have a name assigned to it. A root file location is similar to the root directory of a Windows operating environment. 

***row***
    in relational database management systems, the horizontal component of a table. A row is analogous to a SAS observation. 

***row dimension***
    in the TABULATE procedure, the combination of variables, variable values, and statistics that determine the number and arrangement of rows in the table. See also dimension and dimension expression. 

***row expression***
    in the TABULATE procedure, the part of the TABLE statement that determines the content and appearance of the row dimension by specifying the combination of variables, variable values, and statistics that make up that dimension. See also column expression and page expression. 

***row percentage***
    the ratio of a sum or a frequency count for a single cell of a table to the total sum or frequency count for the row that contains that cell. This ratio is represented as a percentage. 

***row title space***
    the amount of space that is allotted for printing all of the headings for the row dimension of a table as well as two outlining characters. This space is divided equally among all levels of headings for the row dimension. Short form: RTS. 

***RTF destination***
    an ODS destination that produces output written in Rich Text Format for use with Microsoft Word 2000. See also ODS destination.

***RTS***
    See row title space. 

## S

***sampling with replacement***
    a method of taking a sample that allows you to select an item more than once. 

***sampling without replacement***
    a method of taking a sample that does not allow you to select an item more than once. 

***SAS catalog***
    a SAS file that stores many different kinds of information in smaller units called catalog entries. A single SAS catalog can contain different types of catalog entries. See also SAS catalog entry. 

***SAS catalog entry***
    a separate storage unit within a SAS catalog. Each entry has an entry type that identifies its purpose to SAS. Some catalog entries contain system information such as key definitions. Other catalog entries contain application information such as window definitions, Help windows, SAS formats and informats, macros, or graphics output. See also entry type. 

***SAS command***
    a command that invokes SAS. This command can vary depending on the operating environment and site. 

***SAS compilation***
    the process of converting statements in the SAS language from the form in which you enter them to a form that is ready for SAS to use. 

***SAS console log***
    a file that contains information, warning, and error messages if the SAS log is not active. The SAS console log is normally used only for fatal system initialization errors or for late-termination messages. See also SAS log. 

***SAS data file***
    a type of SAS data set that contains data values as well as descriptor information that is associated with the data. The descriptor information includes information such as the data types and lengths of the variables, as well as the name of the engine that was used to create the data. See also SAS data set and SAS data view. 

***SAS data set***
    a file whose contents are in one of the native SAS file formats. There are two types of SAS data sets: SAS data files and SAS data views. SAS data files contain data values in addition to descriptor information that is associated with the data. SAS data views contain only the descriptor information plus other information that is required for retrieving data values from other SAS data sets or from files whose contents are in other software vendors' file formats. See also descriptor information. 

***SAS data set option***
    an option that appears in parentheses after a SAS data set name. Data set options specify actions that apply only to the processing of that SAS data set. See also engine/host option and SAS system option. 

***SAS data view***
    a type of SAS data set that retrieves data values from other files. A SAS data view contains only descriptor information such as the data types and lengths of the variables (columns) plus other information that is required for retrieving data values from other SAS data sets or from files that are stored in other software vendors' file formats. SAS data views can be created by the SAS DATA step and by the SAS SQL procedure. 

***SAS date value***
    an integer that represents a date in SAS software. The integer represents the number of days between January 1, 1960, and another specified date. For example, the SAS date value 366 represents the calendar date January 1, 1961. 

***SAS datetime value***
    an integer that represents a date and a time in SAS software. The integer represents the number of seconds between midnight, January 1, 1960, and another specified date and time. For example, the SAS datetime value for 9:30 a.m., June 5, 2000, is 1275816600. 

***SAS execution***
    the process in which SAS follows the instructions given by SAS statements to perform an action. 

***SAS expression***
    a sequence of operands and operators that form a set of instructions that SAS processes and which resolve to a single value. SAS expressions are used in SAS program statements to create variables, to assign values, to calculate new values, to transform variables, and to perform conditional processing. SAS expressions can resolve to numeric values, character values, or Boolean values. 

***SAS file***
    a specially structured file that is created, organized, and, optionally, maintained by SAS. A SAS file can be a SAS data set, a catalog, a stored program, an access descriptor, a utility file, a multidimensional database file, a financial database file, a data mining database file, or an item store file. 

***SAS filename extension***
    a standard filename identifier that conveys information about these file attributes: 1) the SAS engine that was used to create the file, 2) the architecture of the operating environment in which the file was created, and 3) the member type. SAS uses filename extensions to identify the appropriate files for access. 

***SAS initialization***
    the process of setting global characteristics that must be in effect in order for a SAS session to begin. SAS performs initialization by setting certain SAS system options called initialization options. SAS initialization happens automatically when you invoke SAS. 

***SAS Installation Representative***
    the contact person at a SAS customer site who receives either the media, the download information, or the authorization codes that are required in order to install the SAS software or to renew the license for the SAS software. The representative is typically an employee of the SAS customer. 

***SAS language***
    a programming language that includes procedures for data analysis and reporting, statements and functions for managing SAS files and manipulating data, options that define the SAS environment, a macro facility, Help menus, and a windowing environment for text editing and file management. 

***SAS log***
    a file that contains a record of the SAS statements that you enter, as well as messages about the execution of your program. In some cases, the SAS log can also contain output from the DATA step and from certain procedures. See also SAS console log. 

***SAS name***
    a name that is assigned to items such as SAS variables and SAS data sets. For most SAS names, the first character must be a letter or an underscore. Subsequent characters can be letters, numbers, or underscores. Blanks and special characters (except the underscore) are not allowed. However, the VALIDVARNAME= system option determines what rules apply to SAS variable names. The maximum length of a SAS name depends on the language element that it is assigned to. Many SAS names, such as names of DATA step variables and array names, can be 32 characters long. Others, such as librefs and filerefs, have a maximum length of 8 characters. 

***SAS operator***
    See operator. 

***SAS procedure***
    a program that provides specific functionality and that is accessed with a PROC statement. For example, SAS procedures can be used to produce reports, to manage files, or to analyze data. Many procedures are included in SAS software. In addition, users can use SAS/TOOLKIT software to write their own procedures. These are called user-written procedures. See also user-written procedure. 

***SAS program***
    a group of SAS statements that guide SAS through a process or series of processes in order to read and transform input data and to generate output. The DATA step and the procedure step, used alone or in combination, form the basis of SAS programs. 

***SAS registry***
    an item store that contains configuration data for one or more SAS software products. For example, the SAS registry stores information about data libraries and file shortcuts that SAS assigns at startup, about menu definitions for the SAS Explorer pop-up menus, and about printers that have been defined. The SAS registry is usually viewed with the Registry Editor, which is invoked with the REGEDIT command. See also item store. 

***SAS session***
    See session. 

***SAS statement***
    a string of SAS keywords, SAS names, and special characters and operators that instructs SAS to perform an operation or that gives information to SAS. Each SAS statement ends with a semicolon. 

***SAS system option***
    an option that affects the processing of an entire SAS program or interactive SAS session from the time the option is specified until it is changed. Examples of items that are controlled by SAS system options include the appearance of SAS output, the handling of some files that are used by SAS, the use of system variables, the processing of observations in SAS data sets, features of SAS initialization, and the way SAS interacts with your host operating environment. 

***SAS time value***
    an integer that represents a time in SAS software. The integer represents the number of seconds between midnight of the current day and another specified time value. For example, the SAS time value for 9:30 a.m. is 34200. 

***SAS windowing environment***
    an interactive windowing interface to SAS software. In this environment you can issue commands by typing them on the command line, by pressing function keys, or by selecting items from menus or menu bars. Within one session, you can perform many different tasks, including preparing and submitting programs, viewing and printing results, and debugging and resubmitting programs. 

***SAS XML LIBNAME engine***
    the SAS engine that processes XML documents. The engine exports an XML document from a SAS data set by translating the proprietary SAS file format to XML markup. The engine also imports an external XML document by translating XML markup to a SAS data set. 

***SAS XML Mapper***
    a graphical interface that you can use to create and modify XMLMaps for use by the SAS XML LIBNAME engine. The SAS XML Mapper analyzes the structure of an XML document and generates basic XML markup for the XMLMap. 

***SAS/ACCESS view***
    a type of file that retrieves data values from files that are stored in other software vendors' file formats. You use the ACCESS procedure of SAS/ACCESS software to create SAS/ACCESS views. See also view descriptor. 

***SAS/SHARE client***
    a SAS session that requests access to remote data by means of a SAS/SHARE server. See also SAS/SHARE server.

***SAS/SHARE server***
    the result of an execution of the SERVER procedure, which is part of SAS/SHARE software. A server runs in a separate SAS session that services users' SAS sessions by controlling and executing input and output requests to one or more SAS libraries. 

***SASEDOC engine***
    a SAS engine that associates a SAS libref (library reference) with one or more ODS output objects that are stored in an ODS document. 

***Sashelp library***
    a SAS library supplied by SAS software that stores the text for Help windows, default function-key definitions and window definitions, and menus. 

***SASROOT***
    a term that represents the name of the directory or folder in which SAS is installed at your site or on your computer. 

***Sasuser library***
    a default, permanent SAS library that is created at the beginning of your first SAS session. The Sasuser library contains a Profile catalog that stores the customized features or settings that you specify for SAS. You can also store other SAS files in this library. 

***Sasuser.Profile catalog***
    a SAS catalog in which SAS stores information about attributes of your SAS windowing environment. For example, this catalog contains function-key definitions, fonts for graphics applications, window attributes, and other information that is used by interactive SAS procedures. See also SAS catalog. 

***scalability***
    the ability of a software application to function well with little degradation in performance despite changes in the volume of computations or operations that it performs and despite changes in the computing environment. Scalable software is able to take full advantage of increases in computing capability such as those that are provided by the use of SMP hardware and threaded processing. See also scalable software, server scalability, and symmetric multiprocessing. 

***Scalable Performance Data Engine***
    a SAS engine that is able to deliver data to applications rapidly because it organizes the data into a streamlined file format. The SPD Engine also reads and writes partitioned data sets, which enable it to use multiple CPUs to perform parallel I/O functions. Short form: SPD Engine. See also parallel I/O. 

***scalable software***
    software that responds to increased computing capability on SMP hardware in the expected way. For example, if the number of CPUs is increased, the time to solution for a CPU-bound problem decreases by a proportionate amount. And if the throughput of the I/O system is increased, the time to solution for an I/O-bound problem decreases by a proportionate amount. See also server scalability, SMP (symmetric multiprocessing), and time to solution. 

***schedule calendar***
    in the CALENDAR procedure, procedure output that displays observations from one or more SAS data sets in month-by-month calendars. Unlike summary calendars, a schedule calendar can display activities that can have durations of more than one day. 

***seed***
    an initial value from which a random number function or CALL routine calculates a random value. 

***seek operation***
    in table lookup applications, the scanning or search operation involved in using the key variable to access the lookup file. 

***selection field***
    the portion of a window (shown on the display as an underscore) on which you can enter a short command to perform an action, such as B for browse. 

***selection list***
    a list that tells ODS which output objects to send to a specified ODS destination. See also exclusion list.

***selection-field command***
    a command that enables you to perform actions from a selection field in a SAS windowing environment. For example, entering D in the selection field beside the name of a SAS data set in the DIRECTORY window enables you to delete that SAS data set. 

***sequential access***
    a method of file access in which the records are read or written one after the other from the beginning of the file to the end. 

***server***
    a computer system that provides data or services to multiple users on a network. The term 'server' sometimes refers to the computer system's hardware and software, but it often refers only to the software that provides the data or services. In a network, users might log on to a file server (to store and retrieve data files), a print server (to use centrally located printers), or a database server (to query or update databases). In a client/server implementation, a server is a program that waits for and fulfills requests from client programs for data or services. The client programs might be running on the same computer or on other computers. See also client. 

***server scalability***
    the ability of a server to take advantage of SMP hardware and threaded processing in order to process multiple client requests simultaneously. That is, the increase in computing capacity that SMP hardware provides increases proportionately the number of transactions that can be processed per unit of time. See also symmetric multiprocessing and threaded processing. 

***session***
    the activity between invoking and exiting a specific software product. 

***session compiled macro***
    a macro that the macro processor compiles and stores in a SAS catalog in the WORK library. These macros exist only during the current SAS session. Unlike stored compiled macros, session compiled macros cannot be called in any other SAS session. 

***simple expression***
    a SAS expression that uses only one operator. 

***simple index***
    an index that uses the values of only one variable to locate observations. See also composite index.

***site number***
    the number that SAS uses to identify the company or organization to which SAS software is licensed. The site number appears near the top of the log in every SAS session. 

***skewness***
    a measure of the deviation from symmetry of a distribution, or the tendency of values to be more spread out on one side of the mean than the other. 

***SMF***
    See System Management Facility. 

***SMP***
    See symmetric multiprocessing. 

***sort indicator***
    an attribute of a data file that indicates whether a data set is sorted, how it was sorted, and whether the sort was validated. Specifically, the sort indicator attribute indicates the following information: 1) the BY variable(s) that were used in the sort; 2) the character set that was used for the character variables; 3) the collating sequence of character variables that was used; 4) whether the sort information has been validated. This attribute is stored in the data file descriptor information. Any SAS procedure that requires data to be sorted as a part of its process uses the sort indicator. 

***SOURCE entry***
    a type of catalog entry that contains text from SAS text editor windows. 

***source operating environment***
    in the context of moving and accessing SAS files, the operating environment from which you move a SAS file. 

***spawn***
    to start a process or a process thread such as a light-weight process thread (LWPT). See also thread.

***SPD Engine***
    See Scalable Performance Data Engine. 

***SPD Engine data file***
    the data component of an SPD Engine data set. In contrast to SAS data files, SPD Engine data files contain only data; they do not contain metadata. The SPD Engine does not support data views. See also SPD Engine data set. 

***SPD Engine data set***
    a data set created by the SPD Engine that has up to four component files: one for data, one for metadata, and two for any indexes. The minimum number of component files is two: data and metadata. Data is separated from the metadata for SPD Engine file organization. 

***special character***
    in SAS, usually any single keyboard character other than letters, numbers, the underscore, and the blank. 

***split character***
    in some SAS procedures, a character that splits headers across multiple lines. If you use the split character in a column header, the procedure breaks the header when it reaches that character and continues the header on the next line. The split character itself is not part of the column header. 

***SPSS engine***
    the SAS engine that provides read-only access to SPSS files. 

***SQL***
    See Structured Query Language. 

***standard data***
    data in which each digit or character occupies one byte of storage. 

***standardization***
    a method of transforming values of a variable to a different scale based on a particular mean and standard deviation. 

***statement***
    See SAS statement. 

***statement label***
    a SAS name followed by a colon that prefixes a statement in a DATA step so that other statements can direct execution to that statement as necessary, bypassing other statements in the step. 

***statement option***
    a word that you specify in a particular SAS statement and which affects only the processing that that statement performs. 

***statement-style macro***
    a macro that is defined with the STMT option in the %MACRO statement. See also command-style macro and name-style macro.

***stem-and-leaf plot***
    a plot that shows the shape of a distribution with each value separated into a base number, plotted in the stem, and the remaining portion, plotted in the leaf. 

***step boundary***
    a point in a SAS program when SAS recognizes that a DATA step or PROC step is complete. 

***stored compiled DATA step program***
    a SAS file that contains a DATA step program that has been compiled and then stored in a SAS library. You can execute stored compiled programs as needed without having to recompile them. 

***stored compiled macro***
    a macro program that was compiled in a previous session and which was stored in a permanent directory. Unlike session compiled macros, stored compiled macros can be called in any SAS program. 

***stratified random sample***
    a sample that is obtained by dividing a population into non-overlapping parts, called strata, and randomly selecting items from each stratum. 

***Structured Query Language (SQL)***
    a standardized, high-level query language that is used in relational database management systems to create and manipulate objects in a database management system. SAS implements SQL through the SQL procedure. Short form: SQL. 

***style definition***
    a template that specifies instructions for the presentation aspects (color, font face, font size, and so on) of your SAS output. This template determines the overall appearance of the documents that use it. Each style definition is composed of style elements. Style definitions have no effect on the LISTING destination, which produces plain text output. See also style element and table definition. 

***style definition inheritance***
    the concept that a child style definition receives all the style elements, attributes, and statements that are specified in its parent style definition unless the child style definition overrides them. 

***style element***
    a collection of style attributes that each pertain to a particular part of some ODS output. For example, a style element might contain instructions for the presentation of individual table cells. Within the style element, each style attribute specifies a value for one aspect of the presentation. For example, the FLYOVER= attribute specifies the text to display in a tool tip for a cell, and the PRETEXT= attribute specifies the text to place before a cell. See also style definition and table element. 

***style element inheritance***
    the concept that a child style element receives all of the style attributes that are specified in its parent style element, unless the child style element overrides those attributes. 

***subquery***
    a query-expression that is nested as part of another query- expression. Depending on the clause that contains it, a subquery can return a single value or multiple values. See also query-expression. 

***subtable***
    in the TABULATE procedure, the group of cells that is produced by crossing a single element from each dimension of the TABLE statement when one or more dimensions contain concatenated elements. Each subtable of a larger table could be produced separately by rewriting the TABLE statement as several simple TABLE statements with no concatenated elements. 

***summary calendar***
    in the CALENDAR procedure, procedure output that displays observations from SAS data sets in month-by-month calendars. A summary calendar can display only activities that have durations of one day or less. 

***summary function***
    a function that summarizes or describes a group of data values, which are usually numeric data values. For example, SUM and MEAN are summary functions. See also descriptive statistic. 

***summary line***
    in the REPORT procedure, a break line that summarizes statistics and computed variables. 

***summary report***
    a report that provides a concise overview of information that is derived from one or more data sources. Summary information is typically calculated using descriptive statistics such as SUM, MEAN, and RANGE. See also descriptive statistic. 

***summary table***
    output that provides a concise overview of the information in a data set. 

***symbol table***
    the area in which the macro processor stores all macro variables and macro statement labels for a particular scope. 

***symbolic variable***
    another term for macro variable. See also macro variable.

***symmetric multiprocessing***
    a hardware and software architecture that can improve the speed of I/O and processing. An SMP machine has multiple CPUs and a thread-enabled operating system. An SMP machine is usually configured with multiple controllers and with multiple disk drives per controller. Short form: SMP. 

***syntax checking***
    the process by which SAS checks each SAS statement for proper usage, correct spelling, proper SAS naming conventions, and so on. 

***syntax error***
    an error in the spelling or grammar of a SAS statement. SAS finds syntax errors as it compiles each SAS step before execution. See also data error and programming error. 

***System Management Facility***
    a feature of the z/OS and OS/390 operating systems that provides information about the computing resources that the operating system utilizes when it runs a job. Short form: SMF. 

***system option***
    See SAS system option. 

## T

***table alias***
    a temporary, alternate name for a table that is specified in a FROM clause. Table aliases are optionally used to qualify column names when tables are joined. 

***table cell***
    See cell. 

***table definition***
    a set of instructions that describe how to format output in the Output Delivery System (ODS). 

***table element***
    a collection of table attributes that each pertain to a particular column, header, or footer in a table in ODS output. 

***table lookup***
    a processing technique in which information is retrieved from an auxiliary source, based on the values of variables in the primary source. 

***table source***
    in the SQL Query Window, a collection of one or more data sources to be queried. 

***tagset***
    a template that defines how to create a type of markup language output from a SAS format. Tagsets produce markup output such as Hypertext Markup Language (HTML), Extensible Markup Language (XML), and LaTeX. See also markup language. 

***tagset definition***
    a template that specifies instructions for creating a markup language for your SAS output. The resulting output contains embedded instructions in order to define layout and some content. Each tagset definition contains event definitions and event attributes that control the generation of the output. SAS provides tagset definitions for a variety of markup languages. You can use the TEMPLATE procedure to modify any of these SAS tagsets or to create your own tagsets. See also ODS markup family. 

***target operating environment***
    in the context of moving and accessing SAS files, the operating environment to which you move a SAS file. 

***target variable***
    the variable to which the result of a function or expression is assigned. 

***TCP/IP***
    an abbreviation for a pair of networking protocols. Transmission Control Protocol (TCP) is a standard protocol for transferring information on local area networks such as Ethernets. TCP ensures that process-to-process information is delivered in the appropriate order. Internet Protocol (IP) is a protocol for managing connections between operating environments. IP routes information through the network to a particular operating environment and fragments and reassembles information in transfers. 

***template store***
    an item store that contains definitions that were created by the TEMPLATE procedure. Definitions that SAS provides are in the item store Sashelp.Tmplmst. You can store definitions that you create in any template store to which you have write access. See also item store. 

***temporary array elements***
    array elements that behave like variables but that do not appear in the output data set. They have no names and can be referenced only by their array names and dimensions. They are automatically retained, instead of being reset to missing at the beginning of the next iteration of the DATA step. 

***temporary SAS data set***
    a data set that exists only for the duration of the current program or interactive SAS session. Temporary SAS data sets are not available for future SAS sessions. 

***temporary SAS file***
    a SAS file in a SAS library (usually the Work library) that is deleted at the end of the SAS session or job. 

***terabyte***
    2 to the 40th power, or 1,099,511,627,776 (approximately 1.1 trillion) bytes. See also gigabyte, kilobyte, and megabyte.

***text string***
    See character string. 

***text-editing command***
    a command that is used with a particular text editor. 

***thread***
    a single path of execution of a process in a single CPU, or a basic unit of program execution in a thread-enabled operating system. In an SMP environment, which uses multiple CPUs, multiple threads can be spawned and processed simultaneously. Regardless of whether there is one CPU or many, each thread is an independent flow of control that is scheduled by the operating system. See also symmetric multiprocessing, thread-enabled operating system, and threading. 

***threaded I/O***
    I/O that is performed by multiple threads in order to increase its speed. In order for threaded I/O to improve performance significantly, the application that is performing the I/O must be capable of processing the data rapidly as well. See also I/O-bound application. 

***threaded processing***
    processing that is performed in multiple threads in order to improve the speed of CPU-bound applications. See also CPU-bound application. 

***thread-enabled operating system***
    an operating system that can coordinate symmetric access by multiple CPUs to a shared main memory space. This coordinated access enables threads from the same process to share data very efficiently. 

***thread-enabled procedure***
    a SAS procedure that supports threaded I/O or threaded processing. 

***threading***
    a high-performance method of data I/O or data processing in which the I/O or processing is divided into multiple threads that are executed in parallel. In the boss-worker model of threading, the same code for the I/O or calculation process is executed simultaneously in separate threads on multiple CPUs. In the pipeline model, a process is divided into steps, which are then executed simultaneously in separate threads on multiple CPUs. See also parallel I/O, parallel processing, and SMP (symmetric multiprocessing). 

***time to solution***
    the elapsed time that is required for completing a task. Time-to- solution measurements are used to compare the performance of software applications in different computing environments. In other words, they can be used to measure scalability. See also scalability. 

***time value***
    See SAS time value. 

***title***
    a heading that is printed at the top of each page of SAS output or of the SAS log. 

***toggle***
    an option, parameter, or other mechanism that enables you to turn on or turn off a processing feature. 

***token***
    the unit into which the SAS language or the macro language divides input in order to enable SAS to process that input. Tokens (also called words) include items that look like English words (such as variable names) as well as items that do not (such as mathematical operators and semicolons). 

***tokenizer***
    the part of the word scanner that divides input into tokens (also called words). See also token and word scanner.

***tradeoff***
    to allow a program to use more of one resource in order to decrease the use of another resource. 

***trailing at sign***
    a special symbol @ that is used to hold a line of input or output so that SAS can read from it or write to it in a subsequent INPUT or PUT statement. 

***transaction data set***
    in an update operation, the data set that contains the information that is needed in order to update the master data set. See also master data set. 

***transcoding***
    the process of converting the contents of a SAS file from one encoding to another encoding. Transcoding is necessary if the session encoding and the file encoding are different, such as when transferring data from a Latin 1 encoding under UNIX to a German EBCDIC encoding on an IBM mainframe. See also encoding. 

***transferring SAS files***
    the process of delivering SAS files from a source operating environment to a target operating environment, either by means of a magnetic medium or across a network. See also copying SAS files. 

***transport engine***
    a facility that transforms a SAS file from its operating environment-specific internal representation to transport format. See also transport format, transport file, and transporting SAS files. 

***transport file***
    a sequential file that contains a SAS library, a SAS catalog, or a SAS data set in transport format. You can use transport files to move SAS data libraries, SAS catalogs, and SAS data sets from one operating environment to another. See also transporting SAS files. 

***transport format***
    either of two file formats that are used to move SAS data sets, SAS data libraries, and SAS catalogs from one operating environment to another. One transport format is produced when the COPY procedure is used with the XPORT engine. The other transport format is produced by the CPORT and CIMPORT procedures. Each of these transport formats is the same in all operating environments. See also transporting SAS files, transport file, and transport engine. 

***transporting SAS files***
    the process of putting SAS files into transport format and moving them between incompatible operating environments. The transport process creates a transport file in the source operating environment, transfers the transport file to the target operating environment, and restores the transport file to the native format in the target operating environment. If the source and target operating environments run different versions of SAS, the transport process implicitly converts the file only from an earlier version of SAS to a later version. See also architectural compatibility, transport file, transport format, converting SAS files, and transferring SAS files. 

***two-dimensional array***
    a grouping of variables of the same type under a single name with two dimensions. When processed, this grouping of variables produces results that can be displayed in columns and rows. See also multidimensional array and one-dimensional array. 

***two's complement arithmetic***
    a type of arithmetic based on the binary system that determines how the computer represents signed numbers. 

## U

***Unicode***
    a 16-bit encoding that supports the interchange, processing, and display of characters and symbols from dozens of writing systems, for a total of up to 65,536 characters. Unicode includes all characters from most modern written languages as well as characters from some historical languages. 

***union join***
    a type of join that returns all rows with their respective values from each input table. Columns that do not exist in one table will have null (missing) values for those rows in the result table. See also join. 

***Universal Printing***
    a feature of SAS software that enables you to send SAS output to PDF, Postscript, GIF, PNG, SVG, and PCL files, as well as directly to printers. The Universal Printing system also provides many options that enable you to customize your output, and it is available in all of the operating environments that SAS supports. 

***unquoting***
    in the SAS macro facility, the process of restoring the meaning of a quoted item. See also quoting.

***updating***
    a process in which SAS replaces the values of variables in the master data set with values from observations in the transaction data set. 

***User library***
    a SAS library to which the libref User has been assigned. When the libref User is defined, SAS data sets that have one-level names are stored in this library instead of in the temporary Work library. 

***user-written CALL routine***
    a CALL routine written in C, PL/I, FORTRAN, or IBM 370 assembler language using SAS/TOOLKIT software. See also CALL routine.

***user-written format***
    a format that you define with the FORMAT procedure or with C, PL/I, FORTRAN, or IBM 370 assembler language using SAS/TOOLKIT software. 

***user-written function***
    a function written in C, PL/I, FORTRAN, or IBM 370 assembler language using SAS/TOOLKIT software. See also function.

***user-written informat***
    an informat that you define with the FORMAT procedure or with C, PL/I, FORTRAN, or IBM 370 assembler language using SAS/TOOLKIT software. See also informat. 

***user-written procedure***
    a procedure written in C, PL/I, FORTRAN, or IBM 370 assembler language using SAS/TOOLKIT software. See also SAS procedure.

## V

***variable***
    a column in a SAS data set or in a SAS data view. The data values for each variable describe a single characteristic for all observations. Each SAS variable can have the following attributes: name, data type (character or numeric), length, format, informat, and label. 

***variable attribute***
    any of the following characteristics that are associated with a particular variable: name, label, format, informat, data type, and length. 

***variable type***
    the classification of a variable as either numeric or character. Type is an attribute of SAS variables. 

***view***
    a generic term (used by many software vendors) for a definition of a virtual data set (or table). The definition is named and stored for later use. A view contains no data; it merely describes or defines data that is stored elsewhere. See also SAS data view. 

***view descriptor***
    a file created by SAS/ACCESS software that defines part or all of the database management system (DBMS) data or PC file data that is described by an access descriptor. The access descriptor describes the data in a single DBMS table, DBMS view, or PC file. See also access descriptor. 

## W

***WHERE clause***
    one or more WHERE expressions used in a WHERE statement, a WHERE function, or a WHERE= data set option. See also WHERE expression.

***WHERE expression***
    a type of SAS expression that specifies a condition for selecting observations for processing by a DATA step or a PROC step. WHERE expressions can contain special operators that are not available in other SAS expressions. WHERE expressions can appear in a WHERE statement, a WHERE= data set option, a WHERE clause, or a WHERE command. See also SAS expression and WHERE processing. 

***WHERE processing***
    a method of conditionally selecting observations for processing in a DATA or PROC step. WHERE processing involves using a WHERE expression in a WHERE statement, a WHERE= data set option, a WHERE clause, or a WHERE command. See also WHERE expression. 

***windowing environment***
    See SAS windowing environment. 

***word***
    in the SAS programming language, a collection of characters that communicates a meaning to SAS and which cannot be divided into smaller units that can be used independently. A SAS word can contain a maximum of 32,767 characters. See also token. 

***word queue***
    a temporary storage area in SAS from which the word scanner examines tokens (words) before processing them further (as in macro processing) or making the tokens available to the SAS compiler. 

***word scanner***
    the component of SAS that examines all tokens (words) in a SAS program and moves the tokens to the correct component of SAS for processing. 

***Work library***
    a temporary SAS library that is automatically defined by SAS at the beginning of each SAS session or SAS job. Unless you have specified a User library, any newly created SAS file that has a one- level name will be placed in the Work library by default and will be deleted at the end of the current SAS session or job. 

***workdays data set***
    in the CALENDAR procedure, a SAS data set that defines workshifts that are named in a calendar data set. Each variable in the workdays data set contains one daily schedule of alternating work and nonwork periods. See also calendar data set. 

## X

***XML***
    See Extensible Markup Language. 

***XML engine***
    See SAS XML LIBNAME engine. 

***XMLMap***
    a file that contains XML tags that tell the SAS XML LIBNAME engine how to interpret an XML document. 

***XPORT engine***
    the SAS transport engine. This engine accesses SAS files in transport format. See also transport engine and transport format.

## Y

***youngest version***
    the historical version of a data set that is chronologically closest to the base version in a generation group. See also base version, generation data set, generation group, and historical version. 

## Z

***zoned decimal data***
    a method of encoding decimal numbers in which each digit requires one byte of storage. The last byte contains the number's sign as well as the last digit. See also packed decimal data. 
