# <!-- short title, representative of the requirement -->

<!-- Grounding in ISO/IEC/IEEE 29148:2018:
     Â§5.2.8.2, Â§9.6.10 c): each requirement has a unique identifier, such as a number, name tag or
     mnemonic. Once assigned it is never changed and never reused, even if the requirement is
     deleted. -->

## Statement

<!-- Write a single, verifiable requirement statement. Use active voice, and state what is needed,
     not how to implement it.

     Grounding in ISO/IEC/IEEE 29148:2018:
     Â§3.1.19: a requirement translates or expresses a need and its constraints and conditions.
     Â§5.2.4 and Figure 1: name the subject and what it MUST do, or the constraint on it, as
       [Condition] [Subject] [Action] [Object] [Constraint of Action]
     dropping [Condition], and the comma after it, where none applies. A condition (Â§3.1.6) is a
     measurable qualitative or quantitative attribute that says when the requirement applies.
     Â§5.2.4 keywords: agree in advance on the keywords that signal a requirement. This template uses
     the key words of RFC 2119 where the standard's common approach uses "shall". MUST is an
     absolute requirement and MUST NOT an absolute prohibition. SHOULD allows a deviation for a
     valid reason whose implications are understood, and MAY marks an optional item. Only
     capitalized key words have this meaning (RFC 8174). State requirements positively, in active
     voice, and avoid "MUST be able to".
     Â§5.2.7: state what is needed, not how, and avoid these unbounded or ambiguous terms:
       superlatives ("best", "most")
       subjective language ("user friendly", "easy to use", "cost effective")
       vague pronouns ("it", "this", "that")
       ambiguous adverbs and adjectives ("almost always", "significant", "minimal")
       ambiguous logic ("or", "and/or")
       open-ended terms ("provide support", "but not limited to", "as a minimum")
       comparatives ("better than", "higher quality")
       loopholes ("if possible", "as appropriate", "as applicable")
       totality terms ("all", "always", "never", "every")
       references that omit the date, the version number or the applicable parts
     Â§5.2.5: a requirement is necessary, appropriate, unambiguous, complete, singular, feasible,
     verifiable, correct and conforming.
     Â§9.6.12: define the fundamental actions the software takes in accepting and processing the
     inputs and in producing the outputs:
       a) validity checks on the inputs
       b) the exact sequence of operations
       c) responses to abnormal situations: overflow, communication facilities, hardware faults and
          failures, and error handling and recovery
       d) the effect of parameters
       e) the relationship of outputs to inputs, including input/output sequences and the formulas
          converting input to output
     Â§9.6.10 d): describe every input (stimulus) and every output (response). Record that detail
     below the statement, or in a linked specification referenced under Supporting Information.
     Â§9.6.12 allows splitting a requirement into sub-functions without implying the same split in
     the design. -->

<condition>, <subject> MUST <action> <object> <constraint of action>.

## Rationale

<!-- State the reason the requirement is needed, without restating it, and point to the analysis,
     modeling, simulation or other objective evidence behind it.

     Grounding in ISO/IEC/IEEE 29148:2018:
     Â§5.2.8.2: the rationale for establishing each requirement should be captured.
     Â§5.2.7: assumptions about a requirement shall be documented and validated in one of its
     attributes, and the standard names rationale as that attribute.
     Â§9.6.8: dependencies are factors that are not design constraints, but whose change would change
     the requirement. -->

<rationale, assumptions, dependencies>

## Success Criteria

<!-- List the criteria that decide whether the requirement is met. State each one in measurable
     terms, so that it is independently verifiable and unambiguous, and reference the test cases or
     data that will show it.

     Grounding in ISO/IEC/IEEE 29148:2018:
     Â§6.5.2.2: the verification method defines how compliance is proven, including the success
     criteria and the closure approach, so these criteria and the method below are written together.
     Â§5.2.5 Verifiable: the requirement is worded so its realization can be proven, and
     verifiability improves when it is measurable.
     Â§9.6.14, on performance requirements, shows what measurable means: "95 % of the transactions
     shall be processed in less than 1 s" rather than "an operator shall not have to wait for the
     transaction to complete". -->

- <criterion>

## Verification Method

<!-- Select the verification method from the list below, and state how it will be applied to this
     requirement.

     Grounding in ISO/IEC/IEEE 29148:2018:
     Â§6.5.2.2 defines four methods. Inspection examines the item against its documentation. Analysis
     uses analytical data or simulation to show theoretical compliance, and may argue from
     similarity to an already verified item. Demonstration shows the function working, with little
     or no instrumentation. Test measures behavior quantitatively under controlled conditions.
     NOTE 2 to Â§6.5.2.2: certification is the alternative commonly added, a written assurance,
     usually from a third party, that the item was built to an accepted standard.
     Â§6.5.2.2: also name who leads the verification, when in the project it happens (an event, not a
     calendar date), and where. For inspection, name the documents compared. For analysis, name the
     analysis, the tools or methods, the source of input data and how it is analyzed, all agreed
     with the acquirer. For demonstration, name the witnesses, the steps and any special resources.
     For test, name the environment, the data to collect and how results are analyzed.
     Â§6.5.2.2, Â§6.5.2.3: record the method, its criteria and its result in a requirements
     traceability matrix, so the trace shows how each requirement was verified. -->

Inspection | Analysis | Demonstration | Test | Certification

## Supporting Information

<!-- Provide supporting context, links, and references that help implementers and verifiers
     understand the requirement, together with any open issues or pending decisions that could
     affect it.

     Grounding in ISO/IEC/IEEE 29148:2018:
     Â§9.6.20 Supporting information: sample input and output formats, cost analysis studies or user
     survey results, background that helps the reader, a description of the problem the software
     solves, and packaging instructions for the code and media. State explicitly whether any of it
     is part of the requirements.
     Â§6.4.3.5 d) 2): record the trace links in this section, upward to the parent requirements and
     stakeholder needs, downward to any lower-level requirements and to the design and code that
     implement it, and across to the tests that verify it. -->

- <item>