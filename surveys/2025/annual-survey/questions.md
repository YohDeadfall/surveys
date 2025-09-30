# Survey questions

Whether or not you use the Rust Programming Language <https://rust-lang.org> today, we want to hear from you!

The Rust Community Team has created this survey to help us gauge how we're doing, what can be improved, and how we can best engage with all of you as we move forward.

This is your chance to have a say in the development priorities of Rust.

Your answers will be anonymous. Any personal data you submit as a part of this survey will be handled in accordance with our policy as described in our [Frequently Asked Questions](https://github.com/rust-lang/surveys/blob/main/documents/Community-Survey-FAQ.md).

We estimate it will take about 10-25 minutes to complete.

## Rust Usage

### Do you use Rust?

Type: select one

- Yes, I use Rust (for any purpose, even if you're just learning) [`NEXT`](#your-rust-experience)
- No, I don't currently use Rust, but I have in the past [`NEXT`](#for-previous-rust-users)
- No, I have never used Rust [`NEXT`](#for-non-rust-users)

> **justification**
>
> Fundamental for cohort analysis

## For previous Rust users

### As you have indicated that you're not currently using Rust, why not?

Type: select all that apply

- Missing language features
- Missing libraries
- Missing tools
- Too difficult to learn
- Community was rude, unwelcoming, or otherwise off-putting
- I prefer to use another language
- I no longer have the opportunity to use Rust due to factors outside my control
- I plan to use it in the future once an opportunity comes up
- Other

### Tell us more:

Type: free form (optional)

> **SURVEY FLOW**
>
> Skip to `### Are you employed full- or part-time (including paid internships)?`

## For non-Rust users

### Why don't you use Rust?

Type: select all that apply

- Rust does not help me achieve my goals
- Missing language features
- Missing libraries
- Missing tools
- Too difficult to learn or learning will take too much time
- Community was rude, unwelcoming, or otherwise off-putting
- I prefer to use another language
- I can't use Rust due to factors outside my control
- I haven't got around to it
- Other

### Tell us more:

Type: free form (optional)

> **SURVEY FLOW**
>
> Skip to `### Are you employed full- or part-time (including paid internships)?`

## Rust usage and learning experience

### On average, how often do you use Rust?

Type: select one

- Daily or nearly so
- Weekly or nearly so
- Monthly or nearly so
- Rarely

> **justification**
>
> This can be useful demographic information as a proxy for how "important" Rust is
> in someone's technical life.
>
> We deliberately use calendar time for this question to gauge how "serious" the
> programmer's use of Rust is. This does mean that we will group together, for example,
> those who program once a week but always in Rust and those who program daily but
> use Rust once a week.

### How would you rate your Rust expertise?

Type: select one

- I can't write Rust code
- I can write simple programs in Rust
- I can write useful, production-ready code, but it is a struggle
- I am productive writing Rust

> **justification**
>
> Useful for cohort analysis, i.e., for other questions we can query if answers are significantly different for beginners vs advanced users.
>
> Previously this question was a 1-10 ranking. Having specific labels can help with consistency across responses. Additionally, having 10 choices
> was too specific (i.e., what's the difference between a 7 and 8?) where as with the new answers, we have a better idea of what the differences 
> between answers actually mean.

### When did you learn to program in Rust?

**Note**: while you may continue to try to improve your Rust skills, for this question assume "learning to program in Rust"
means spending the *majority* of your time with Rust consuming learning materials or coding *in order to learn* (as opposed to achieving
some other goal). If your learning process spans several of the listed time periods, pick the one where you felt you learned *the most*.

Type: select one (optional)

- I'm still *actively* trying to learn Rust
- During 2025
- During 2023 or 2024
- During 2021 or 2022
- During 2020 or 2019
- During 2018 or before

> **justification**
>
> Useful for cohort analysis, i.e., for other questions we can understand if *when* someone learned Rust impacts their views on things.
>
> The time periods used as answers try to reflect the major "epochs" of Rust history (i.e., pre-1.0, 2015 edition pre and post new error style,
> and 2018 edition) as well as the most recent past. We use whole years even though this doesn't line up perfectly with these epochs. Learning
> Rust in early 2015 was likely similar to the experience of learning Rust post 1.0 while before that the language was changing rapidly.
> We explicitly use years instead of asking for which Rust edition someone learned because the former is often much easier for respondents to know.
> It's also helpful to be more specific than an edition, and it's fairly easy to know which edition someone likely used based on the year they
> learned Rust.

### If you consumed learning material about Rust, which kind of material did you consume?

Type: select all that apply (optional)

- Books ("The Rust Programming Language", "Rust for Rustaceans", etc.)
- Online exercises (Rustlings, 100 Exercises To Learn Rust, etc.)
- Videos or live-streams
- Blog posts
- Documentation
- Source code of Rust crates
- Online courses, webinars
- In-person training
- University learning materials
- Other (please specify)

> **justification**
>
> Getting data here seems helpful for guiding users / recommending public content.

### Are you currently taking a course that uses or teaches Rust OR have you taken a course of this type in the last year?

Type: select one (optional)

- Yes, through a university, school, or other educational institution
- Yes, through my employer, contractor, or consultancy
- No

> **justification**
>
> This question is primarily used to funnel respondents into the more specific questions about the kinds of educational activities they've been a part of.

## Technical questions

### Which operating systems do you use regularly for Rust development?

**Note**: this is specifically about which systems you personally use for development, *not* all the 
systems you target.

Type: select all that apply (optional)

- Linux
- Windows 10/11
- Windows 8.1 or older
- Windows Subsystem for Linux
- macOS
- Other (open response)

> **justification**
>
> In general we'd like to know which operating systems are most used as dev machines in the community.
>
> We're using "Linux" here rather than grouping all UNIXes together, to allow
> us to gauge interest in specific other UNIXes via the fill-in-the-blank
> "other" option. If we grouped UNIXes together, users of other UNIX systems
> wouldn't be visible; let's try to capture the level of interest in those
> systems. As with many questions with an open "other" response; if any
> specific answer appears frequently, we can add it to future surveys to reduce
> the amount of work needed to process responses.

### Which operating systems or runtimes do you develop Rust software for?

**Note**: this is specifically about which operating system or runtime you **target** not which system you use
for development nor which specific architectures (e.g., x86 vs ARM) you target.

Type: select all that apply (optional)

- Linux (desktop or server)
- Windows 10/11
- Windows 8.1 or older
- macOS
- iOS
- Android
- Embedded platforms (with an operating system)
- Embedded platforms (bare metal)
- WebAssembly (for browsers)
- WebAssembly (for other hosts)
- Explicitly platform-independent (e.g., a library which does not interact with the operating system)
- Other (open response)

> **justification**
>
> This question can be used to figure out roughly what systems are being targeted as well as 
> what OS stack is being developed against (i.e., desktop/server OS, mobile OS, embedded OS, bare metal)
>
> We're using "Linux" here rather than "*nix" or similar, with the same
> justification as in the "Which operating systems do you use" question.
>
> We specifically care about the runtime environment being targeted. ISA and other machine specifics are
> not what matters.

### Which editor or IDE setup do you use with Rust code on a regular basis?

Type: select all that apply (optional)

- VS Code
- vi/vim/neovim
- IntelliJ/CLion/other JetBrains IDE + Rust plugin
- Rust Rover (dedicated IntelliJ Rust IDE)
- Emacs (or derivatives like Doom Emacs, Spacemacs, etc.)
- Sublime Text
- Visual Studio
- Xcode
- Atom
- Helix
- Zed
- Other (open response)

> **justification**
>
> It is good to know which editor is the most preferred for Rust development. This
> can change investment strategies for further IDE development.
>
> Note: previously this question included different 'drivers' of the Rust IDE
> experience (e.g., racer, rls, rust-analyzer). Development has consolidated on
> rust-analyzer, and so it's not necessary to find out which is being used.
> If we are curious how far along adoption of rust-analyzer is, we can ask that
> in a separate question, though this is likely easier to find out through download
> numbers.

### Which version(s) of Rust do you use for development?

Type: select all that apply (optional)

- Current stable version
- Previous stable version
- A specific version of stable Rust equal to or newer than 1.83
- A specific version of stable Rust older than 1.83
- Beta release
- Latest nightly
- A specific version of nightly
- Custom fork
- I don't know
- Other

> **justification**
>
> Together with the following question, we can better determine what the spread of 
> version usage is across the community.
> We ask specifically about version 1.83 since it is, at the time of the survey, the 
> version that was released ~1 year prior. Additionally, at the time of this writing
> all major Linux distros have a version equal to or newer than this version.

### If you use nightly, why?

Type: select all that apply (optional)

- I don't use nightly
- Out of habit
- For a particular language feature or set of language features I need
- I like to have access to all the latest features
- To help test the nightly version for bugs
- To provide design feedback on nightly features
- For testing in CI
- A crate dependency I use requires it
- A tool I use requires it
- To have faster compile times
- Other (open response)

> **justification**
>
> We'd like to know what are the common reasons people use nightly
> so that we can better understand where testers are coming from.

### What is the oldest version of Rust you use for any development task?

(Excluding testing to ensure your code works on that compiler version.)

Type: select one (optional)

- 1.92 (nightly), and then every version from 1.91 to 1.0 in descending order, and "a pre-1.0 version"

> **justification**
>
> To get real data on how many people use older versions of the toolchain to
> inform discussion on MSRVs.

### Do you agree with the following statements on Rust stability?

Type: matrix (optional)

Statements:

- I can upgrade the *stable* compiler version without fear of my code failing to compile
- I can upgrade the *nightly* compiler version without fear of my code failing to compile
- Upgrading to a new *stable* compiler version requires either no changes or extremely small & easy changes to my code
- Upgrading to a new *nightly* compiler version requires either no changes or extremely small & easy changes to my code

Rating:

- Agree
- Disagree

> **justification**
>
> When want to get an impression of how stable the compiler *feels*. Impressions are more important than hard numbers as
> not all users define stability in the same way the compiler does.

### What is your opinion on how fast Rust evolves?

We want to know how do you perceive the speed of development of the Rust language.

Type: select one (optional)

- Rust is already too complex, it should not add or stabilize more significant features
- Rust changes too quickly, I wish it would slow down the pace of development
- I am satisfied with the current pace of development
- Rust changes too slowly, I wish it would add or stabilize features faster
- I don't know or don't care
- Other (open response)

> **justification**
>
> We want to find out if people prefer stability and fewer changes, or if they want to see more features being
> implemented or stabilized.

### Which unimplemented (or nightly only) features are you looking for to be stabilized?

Please mention *Rust compiler or standard library* features that are currently unstable (only available using a nightly release of the Rust compiler) or missing that would in your opinion be beneficial to the Rust ecosystem or to you. This list excludes other tooling around the compiler such as cargo, rustup, rustfmt, etc.

Type: matrix (optional)

Features:

- [Specialization](https://github.com/rust-lang/rust/issues/31844)
- [Generators/coroutines](https://github.com/rust-lang/rust/issues/43122)
- [Async generators/coroutines](https://github.com/rust-lang/rust/pull/118420)
- [Try blocks](https://github.com/rust-lang/rust/issues/31436)
- [Never type](https://github.com/rust-lang/rust/issues/35121)
- [Trait aliases](https://github.com/rust-lang/rfcs/blob/master/text/1733-trait-alias.md)
- [Type Alias Impl Trait (TAIT)](https://rust-lang.github.io/rfcs/2515-type_alias_impl_trait.html)
- [Associated type defaults](https://rust-lang.github.io/rfcs/2532-associated-type-defaults.html)
- [Generic const expressions](https://github.com/rust-lang/rust/issues/76560)
- [Const trait methods](https://github.com/rust-lang/rust/issues/67792)
- [Declarative (macro_rules!) attributes (#[attr]) and derives (#[derive(Trait)])](https://github.com/rust-lang/rust/issues/143549)
- Compile time reflection
- Variadic generics
- [Arbitrary self types](https://github.com/rust-lang/rfcs/blob/master/text/3519-arbitrary-self-types-v2.md)
- [Enum variant types](https://github.com/rust-lang/lang-team/issues/122)
- [Allocator trait and better OOM handling](https://github.com/rust-lang/rust/issues/32838)
- [Stable ABI](https://github.com/rust-lang/rust/issues/111423)
- [Portable SIMD](https://github.com/rust-lang/portable-simd)

Priority:

- Would unblock my use-case
- Would improve my code
- Don't need it
- Don't know what it is

### Are there any features not mentioned above that you would like to be prioritized?

Type: free form (optional)

> **justification**
>
> Allow the cohort to mention specific language features they might be eagerly waiting for, see https://github.com/rust-lang/surveys/pull/234/files#r1347633041

### Which of the following aspects of Rust present non-trivial problems to your programming productivity?

Assess only challenges that you think are impacting your work. If you do not select anything for a given row, we will assume that you do not know or do not care about that aspect.

Type: matrix (optional)

Challenges:

- Implementing logic for tuples of various sizes
- Splitting code across crates (e.g. orphan rule)
- Having to implement Iterator manually
- Not being able to do enough in const fn
- Implementing dynamic library plugins
- Interoperating with other languages (e.g. C or C++)
- Achieving structured concurrency with async code
- Writing executor-agnostic async code
- Writing correct unsafe code
- Borrow checker not allowing valid code
- Slow runtime performance
- Slow compilation
- Large binary size of compiled artifacts
- High disk space usage (e.g. the size of the target folder)
- Encountering compiler bugs (e.g. ICEs a.k.a. internal compiler errors or miscompilations)
- Encountering opaque/unclear compiler error messages
- Subpar IDE support (e.g. some errors are not shown or analysis is slow)
- Subpar debugging experience (e.g. missing value visualizations or async stacktraces)
- Lacking documentation of the Rust language or the standard library

Options:

- Big problem for me
- Could be improved, but does not limit me
- Not an issue for me at all

> **justification**
>
> This question tries to get insights on what people wish the Rust project would improve.

### Are there any challenges not mentioned above that affect your Rust programming productivity?

Type: free form (optional)

> **justification**
>
> Allow the cohort to mention other challenges.

### Which features stabilized in the past 12 months do you use the most?

The text in the parentheses shows in which Rust version was the feature stabilized.

Type: matrix (optional)

Features:

- [Strict provenance API](https://blog.rust-lang.org/2025/01/09/Rust-1.84.0/#strict-provenance-apis) (1.84)
- [Async closures](https://blog.rust-lang.org/2025/02/20/Rust-1.85.0/#async-closures) (1.85)
- [diagnostic::do_not_recommend](https://blog.rust-lang.org/2025/02/20/Rust-1.85.0/#hiding-trait-implementations-from-diagnostics) (1.85)
- [Trait upcasting](https://blog.rust-lang.org/2025/04/03/Rust-1.86.0/#trait-upcasting) (1.86)
- [Anonymous pipes](https://blog.rust-lang.org/2025/05/15/Rust-1.87.0/#anonymous-pipes) (1.87)
- [Let chains](https://blog.rust-lang.org/2025/06/26/Rust-1.88.0/#let-chains) (1.88)
- [Naked functions](https://blog.rust-lang.org/2025/06/26/Rust-1.88.0/#naked-functions) (1.88)

Usage:

- I use it or plan to use it
- I cannot use this feature yet
- I do not need this feature
- I did not know it was stabilized
- I do not know what it is

### How do you build your Rust projects?

Type: select all that apply (optional)

- I use Cargo
- I use some other build system
- I combine Cargo and another build system
- If you use Cargo with (or just use) other build systems, which ones do you use? (open response)

> **justification**
>
> cargo team expressed interest in this, see https://rust-lang.zulipchat.com/#narrow/stream/246057-t-cargo/topic/Rust.20survery.202023/near/393816653

### From where do you download crates to build Rust projects?

Type: select all that apply (optional)

- crates.io
- Custom/local/company registry
- Mirror of crates.io
- Git repositories
- I don't know
- Other

> **justification**
>
> It could be interesting to know how many people use crates.io vs some custom/local/company registry, and how many people are even aware of what registry do they use. See issue surveys#236.

### Do you make use of compiler error codes?

The Rust compiler assigns error codes to certain compiler errors (e.g. *E0308* or *E0509*). There is a [Rust error codes index](https://doc.rust-lang.org/error_codes/error-index.html) that gathers these errors and provides a general description of them. You can access these error descriptions using e.g. `rustc --explain <error-code>`, in the [documentation](https://doc.rust-lang.org/error_codes/error-index.html) or through the [Rust Playground](https://play.rust-lang.org).

Type: select one (optional)

- I read the compiler error index descriptions and find them useful
- I examined the compiler error index descriptions but did not find them useful
- I did not know there is a compiler error index
- Other (open response)

> **justification**
>
> We are currently discussing whether we should keep error codes in the compiler or not. This would be useful as a way to gauge general interest in this feature.

## The Rust community

### Roughly how often do you engage in the following Rust community activities?

Type: matrix (optional)

Activities:

- Produce informational content about Rust (e.g., blogged, live streamed, made a YouTube video, presented at a conference/meetup, etc.)
- Consume informational content about Rust (e.g., blogs, live streams, YouTube videos, etc.)
- Read official Rust communication channels (e.g., This Week in Rust, the official Rust blog, the Rust Bluesky account, etc.)
- Participate in conversations about Rust on social media or websites (Hacker News, r/rust, Twitter, LinkedIn, etc.)
- Attend a Rust meetup or conference (virtual or in-person)
- Write, comment on, contribute to discussion of, or provide edits to an open RFC
- Discuss the Rust project in an official chat or forum (internals.rust-lang.org, Rust Zulip, etc.)
- Open an issue on any repo in the rust-lang GitHub organization
- Contribute code changes (including tests) to any open-source Rust project
- Contribute non-code changes (documentation, comments, etc.) to any open-source Rust project

Frequency:

- More frequently than weekly
- Weekly
- Monthly or less frequently
- Never

> **justification**
>
> We want to understand the nature of contribution to the Rust project both
> to better understand the shape of community involvement and for cohort analysis.

### What has your experience been like in the following Rust community spaces?

Type: matrix

Community Spaces:

- *Official* Rust community forums or chats (users.rust-lang.org, internals.rust-lang.org, the official Rust Discord, or the Rust Zulip)
- *Unofficial* Rust community forums or chats (e.g., reddit.com/r/rust, Hacker News, the Rust *Community* Discord, etc.)
- Community focused on a specific area of Rust software development (e.g. game development, audio, etc.)
- Rust conferences
- Rust meetups or local community events
- Discussions (issues, pull requests, etc.) on a repository *inside* the rust-lang GitHub organization
- Discussions (issues, pull requests, etc.) on a repository *outside* the rust-lang GitHub organization

Choices:

- I feel welcome
- I do not feel particularly welcome or unwelcome
- I feel unwelcome
- I've never participated in this activity

> **justification**
>
> We'd like to know where people are feeling welcome and the degree to which they are feeling welcome.

### If you indicated that you did not feel welcome in the Rust community, are there any details about your experience that you would like to share with us?

Type: free form (optional)

> **justification**
> 
> More detail on the type of situations where people have felt unwelcome can let us better 
> address these issues in the future.

## Rust at work

### Are you employed full- or part-time (including paid internships)?

Type: select one

- Yes
- No [`NEXT`](#please-share-your-assessment-of-the-following-statements-on-rust-employment)

### Do you write or design software in your work?

Type: select one (optional)

- Yes, primarily as an individual contributor (i.e., non-manager)
- I primarily manage others who do
- No [`NEXT`](#to-what-extent-is-rust-currently-being-used-by-your-organisation)

### Are you personally using Rust at work?

Type: select one

- Yes, for the majority of my coding
- Yes, a few times per week on average
- Yes, but I only use it occasionally
- No

> **justification**
>
> We want to establish what percentage of those who could possibly use Rust in a professional setting
> are using Rust in a professional setting. This is most interesting over time.
> Answers to this question should be combined with whether the respondent has ever used Rust.

### To what extent is Rust currently being used by your organisation?

Type: select one

- My organisation makes non-trivial use of Rust (e.g., used in production or in significant tooling)
- My organisation has experimented with Rust or is considering using it
- My organisation has not seriously considered Rust for any use [`NEXT`](#approximately-how-many-total-developers-does-your-organisation-employ)
- I am unsure whether my organisation has considered using or currently uses Rust [`NEXT`](#approximately-how-many-total-developers-does-your-organisation-employ)
- I don't work for a organisation or my organisation does not develop software of any kind [`NEXT`](#please-share-your-assessment-of-the-following-statements-on-rust-employment)

> **justification**
>
> We want to establish how reliant companies are on Rust.

### Which of the following statements apply to your experience using Rust at work?

Type: select all that apply (optional)

Statements:

- Using Rust has helped us achieve our goals
- Adopting Rust has been challenging
- Overall, adopting Rust has slowed down our team
- Using Rust has been worth the cost of adoption
- We're likely to use Rust again in the future

> **justification**
>
> Future potential adopters may want to know how often other's have encountered success.

### Which of the following statements are reasons why you use Rust at work?

Type: select all that apply (optional)

Statements:

- For its performance (i.e., speed, memory footprint, etc.) characteristics
- We need precise control over exactly how our software runs
- Its security and safety properties are important to us
- It allows us to build relatively correct and bug free software
- We find it enjoyable or fun to program in Rust
- We already know Rust so it's our default choice
- We find it easy to prototype with
- We must interact with existing Rust code

> **justification**
>
> The Rust community and potential adopters of Rust have a lot of assumptions of why one would choose Rust for a project.
> This question can help confirm or challenge our assumptions and see how they change over time.

### What about your usage of Rust has been challenging?

Type: free form (optional)

> **justification**
>
> This an opportunity to learn from adopters at companies what they struggle with when adopting Rust.

### In what technology domain(s) is Rust used at your organisation?

Type: select all that apply (optional)

- Audio programming
- Automotive
- Blockchain
- Cloud computing applications
- Cloud computing infrastructure or utilities
- Computer graphics
- Computer games
- Computer networking
- Computer security
- Data science
- Database implementation
- Desktop computer application frontend
- Desktop computer or mobile phone libraries or services
- Distributed systems
- Embedded devices (with operating systems)
- Embedded devices (bare metal)
- HPC (High-performance [Super]Computing)
- IoT (Internet of Things)
- Machine learning
- Mobile phone application frontend
- Programming languages and related tools (including compilers, IDEs, standard libraries, etc.)
- Robotics
- Scientific and/or numerical computing
- Server-side or "backend" application
- Simulation
- Web application frontend
- WebAssembly
- Other (open response)

> **justification**
>
> We want to know roughly what technology stacks are being most often used.
>
> This can be ambiguous and hard to answer. For example, if you're building an operating
> system for a mobile phone, is that embedded, mobile, or something else?
> We want to understand the "shape" of Rust usage, and this question tries to get at that
> by allowing the respondent to select multiple answers.

### Approximately how many total developers does your organisation employ?

**Note**: Don't worry about being precise here! Go with your instinct.

Type: select one (optional)

- Under 10
- 11-49
- 50-99
- 100-500
- 500-1,000
- 1,000-10,000
- Over 10,000

> **justification**
> 
> This question is not that interesting on its own, but it can be used as a sort of cohort for understanding how answers
> change depending on the size of the development effort at a company.
>
> Previously this question used "employees" instead of "developers". It is more appropriate for us to ask about the amount
> of developers at a company vs. the amount of people employed in total.

### Is your organisation planning on hiring Rust developers in the next year?

Type: select one (optional)

- Yes
- No (it is planning to hire other developers)
- No (it is not planning to hire any developers)
- I don't know

> **justification**
>
> This question assess hiring sentiment. Although there is intrinsic uncertainty, it is easy to answer and forward looking.
> It will also be interesting to see what the demand for Rust skills from companies is over time.

### Please share your assessment of the following statements on Rust employment

Type: matrix (optional)

Statements:

- It is easy for junior programmers to find jobs that use Rust for the majority of programming
- It is easy for senior programmers to find jobs that use Rust for the majority of programming
- Existing Rust jobs are attractive

Rating:

- Agree
- Neither agree nor disagree
- Disagree

> **justification**
>
> The flip side of the question asking whether the respondent's company plans on hiring Rust developers, we
> want to know how respondents feel the level of demand for and quality of Rust jobs are.

## Your opinions about Rust

### Which of the following statements about Rust do you feel are true?

Type: select all that apply (optional)

Statements:

- Rust provides a real benefit over other programming languages
- Rust is significantly more complicated to program in than other programming languages
- Rust requires significantly more effort to learn than other programming languages
- Rust code tends to contain significantly fewer bugs than equivalent code written in another programming language would have
- Rust is risky to use in production
- Rust makes me more productive
- Rust is fun to use

> **justification**
>
> There are several "truisms" about Rust that we'd like to get perspective on how true these are for users of Rust.
>
> Note that answers here can be subject to survivorship bias and so extra care should be taken with interpreting results.

### What are your biggest worries for the future of Rust?

Type: select all that apply (optional)

- Not enough usage in the tech industry
- Too much interest from big companies
- Not enough open source contributions to the ecosystem
- Doesn't add a specific feature I want
- Rust doesn't evolve quickly enough
- Instability of the language
- Superseded by an alternative
- Becomes too complex
- Tools and documentation are not accessible enough (e.g., due to language or incompatibility with screen readers)
- Rust Foundation not supporting the Rust project properly (e.g. in financial, infrastructure, legal aspects)
- Project governance does not scale to match the size/requirements of the community
- Developers/maintainers of the language are not properly supported
- I'm not worried
- Other (open response)

> **justification**
>
> Would be useful for leadership to understand the community's fears.

## About you

See [who](./design/who.md).

Your responses to the following questions will help our reviewers conduct cohort analyses and help us better understand the Rust community. Please answer according to your comfort level.  

### Do you consider yourself a member of a group that is underrepresented or marginalized in technology?

Type: select one

- Yes
- No [`NEXT`](#are-you-a-full--or-part-time-student)
- I prefer not to say [`NEXT`](#are-you-a-full--or-part-time-student)

### Which of the following underrepresented or marginalized groups in technology do you consider yourself a part of?

Type: select all that apply (optional)

- Cultural beliefs
- Disabled (physically, mentally, or otherwise)
- Neurodivergent
- Educational background
- Language
- Lesbian, gay, bisexual, queer or otherwise non-heterosexual
- Non-binary gender
- Older or younger than the average developers I know
- Political beliefs
- Racial or ethnic minority
- Religious beliefs
- Trans
- Woman or perceived as a woman
- Other (open response)

### Are you a full- or part-time student?

Type: select one (optional)

- No
- Yes, in secondary/high school
- Yes, in a bachelor's/undergraduate program
- Yes, in a master's program
- Yes, in a doctorate program
- Yes, in a vocational program
- Yes, other (open response)

> **justification**
>
> This will be important for cohort analysis. In particular, we want to
> understand how students at different points in their education view
> topics related to Rust.

### How long have you been programming (in any language, for any reason)?

Type: select one (optional)

- < 1 year
- < 3 years
- < 5 years
- < 10 years
- > 10 years

### Where do you live?

Type: select one (optional)

- List of countries [`NEXT`](#in-what-ways-are-you-comfortable-communicating-about-technical-topics-in-english)
- Other

> **justification**
>
> We'd like to get a geographic understanding of where the community is. To have more structure, a free-form answer
> is not used, and instead we use the country definition according to UN.

### As you selected "Other" from the list of countries above, please enter your territory of residence below:

Type: free form

### In what ways are you comfortable communicating about technical topics in English?

Type: select all that apply (optional)

- I feel comfortable and capable of having a spoken technical conversation in English
- I feel comfortable and capable of having a written technical conversation in English
- I feel comfortable and capable of reading technical documentation in English
- I feel comfortable and capable of consuming a technical talk (e.g., at a conference or meetup) in English
- I feel comfortable and capable of consuming a written technical educational material (e.g., technical books, blog posts, etc.) in English

> **justification**
>
> We want to understand self reported feeling of comfort and capability of communication
> of English since a large portion of the Rust community is and likely will always be in English.

### In which language(s) are you most comfortable when consuming existing technical content (e.g. blog posts, documentation, etc.)?

**IMPORTANT**: Your answer should reflect your **preference** and **not** what you are capable of communicating in. For example, if you feel comfortable and capable of consuming technical communication in both English and Korean, but you always prefer Korean, you should *only* answer Korean as that is your preference.

Type: select all that apply (optional)

- Chinese
- English
- French
- German
- Hindi
- Japanese
- Korean
- Portuguese
- Russian
- Spanish
- Ukrainian
- Other (open response)

> **justification**
>
> We want to understand *preference* of technical communication and how that differs
> from their abilities to consume technical communication in English.
> The languages selected are those which got 50 or more responses in 2021.

## Anything else?

### Is there anything else you'd like to tell us?

Type: free form (optional)

> **justification**
>
> While it's unlikely we'll receive any one piece of feedback from this question that will prove to be super useful, 
> having it in the survey can still be useful. It can help us decide on new questions or perspectives that we want to
> try to capture in future surveys. It also gives respondents a place to give thanks or share a particular opinion they
> hold which can be useful in and of itself.
