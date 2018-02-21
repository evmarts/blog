### Statistics Background

#### Sample Surveys (STAT 344)
- Planning and practice of sample surveys 
- Unequal probability sampling
- Systematic, multistage and stratified sampling 
-  Ratio and regression estimation
-  Aggregation techniques
-  Pilot studies
-  Dealing with nonresponse

**Programming Language**: R

#### Statistical Inference (STAT 305)
- Moment generating functions
- Sampling distribution theory
- Large sample theory and methods of estimation
- Estimating the parameters of a Normal distribution
- Bias and variance of an estimator
- Maximum likelihood estimation
- Likelihood ratio testing
- Bayesian estimation
- Hypothesis testing
- Confidence interval construction
- Analysis of categorical data
- Goodness of fit tests

**Programming Language**: R

#### Finding Relationships in Data (STAT 306)
- Modeling a response variable as a function of several explanatory variables
- Multiple regression for a continuous response 
- Logistic regression for a binary response
- Log-linear models for count data
- Finding low-dimensional structure
- Principal components analysis (PCA)
- Cluster analysis

**Programming Language**: R

#### Time Series and Forecasting (STAT 443)
- Trend and seasonality 
- Autocorrelation
- Stationarity
- Stochastic models including AR, MA, ARMA, ARIMA, SARIMA models
- Exponential smoothing
- Holt-Winters methods 
- Box-Jenkins approach 
- Frequency domain analysis

**Textbook**: Chatfield. The Analysis of Time Series, An Introduction

**Programming Language**: R

### Math Background

#### Calculus I, II, III

#### Stochastic Processes (MATH 303)
- Discrete-time Markov chains
- Poisson processes
- Continuous time Markov chains
- Renewal theory

**Textbook**: Ross. Introduction to Probability Models.

#### Applied Linear Algebra (MATH 307)

- Solving linear equations
- Interpolation 
- Finite difference approximations
- Subspaces, basis and dimension
- The four fundamental subspaces for a matrix
- Graphs and networks
- Projections
- Complex vector spaces and inner product
- Orthonormal bases, orthogonal matrices and unitary matrices
- Fourier series
- Discrete Fourier transform
- Eigenvalues and Eigenvectors
- Hermitian matrices and real symmetric matrices
- Power method
- Recursion relations
- Markov chains
- Singular value decomposition
- Principle component analyis (PCA)
- Applications of linear algebra to problems in science and engineering
- Use of computer algebra systems for solving problems in linear algebras

**Textbook**: Strang. Linear Algebra and Its Applications

**Programming Language**: MATLAB

#### Numerical Computation for Algebraic Problems (CPSC 302)

- Analysis of round-off errors
- Numerical techniques for basic mathematical processes
- Solving nonlinear equations in one variable:
	- fixed point iteration
	- bisection method
	- Newton's method 
	- secant method
- Direct methods for solving linear systems
	- Gaussian elimination algorithm
	- LU decomposition algorithm
	- Gaussian elimination with partial pivoting algorithm
	- Cholesky decomposition algorithm
	- Condition number of a matrix
	- Sparse and banded matrices
- Solving linear least squares problems
	- Normal equations
	- QR decomposition
	- QR least squares via Givens rotations and Householder transformations
- Iterative methods for linear systems
	- Fixed point iteration
	- Jacobi method
	- Gauss-Seidel method
	- SOR
	- Gradient descent
	- Conjugate gradient
- Eigenvalue problems
	- Power method (with inverse and shift modifications)

**Textbook**: Ascher, Greif. A First Course in Numerical Methods

**Programming Language**: MATLAB

#### Numerical Approximation and Discretization (CPSC 303) TODO

- Analyis of round errors
- Numerical techniques for basic mathematical processes involving discretization, and their analysis. 
- Polynomial interpolation
	- Monomial basis
	- Lagrange basis
	- Newton's basis
	- Chebyshev points
	- Osculating polynomials
- Piecewise polynomial interpolation
	- Piecewise Hermite interpolation
	- Splines
- Numerical differentiation
	- Deriving differentiation formulas
	- Difference formulas using polynomial interpolation
	- Roundoff errors
	- Richardson extrapolation
- Numerical integration
	- Basic quadrature rules
	- Composite numerical integration
	- Gaussian quadrature
	- Adaptive quadrature
- Numerical solution of initial value ordinary differential equations
	- Mathematical modelling of an outbreak of zombie infection
	- Euler's method
	- Runge-Kutta methods
	- Multistep methods
	- Absolute stability and stiffness
	- Error estimation

**Textbook**: Ascher, Greif. A First Course in Numerical Methods

**Programming Language**: MATLAB

### Computer Science Background

#### Intermediate Algorithm Design and Analysis (CPSC 320)
- Asymptotic analysis
- Divide and conquer algorithms
- Graphs
- Greedy algorithms
- Dynamic programming
- NP-completeness
- Study of classic problems:
	- Vertex cover
	- Set cover
	- Graph colouring
	- Hamiltonin path, cycles
	- Travelling salesman
	- Steiner tree
	- Subset sum
	- Knapset
	- SAT
	- Independent set
	- Set packing
- Choosing which algorithm technique, such as divide and conquer, greedy strategies, search or dynmaic programming is suitable for a program
- Choosing appropriate data structures to represent a given problem
- Recognizing similar properties between different problems

**Textbook**: Kleinberg, Tardos. Algorithm Design

#### Software Engingeering (CPSC 310)
- REST and Async programming
- Software specifications
- Agile development
- Object-oriented design principles
- Design patterns
- Automated testing
- Term project: Query engine
	- Promise objects
	- Reading, parsing, writing large datasets
	- REST endpoints
	- packages: restify, jszip, parse5, mocha, chai

**Programming Language**: Typescript 
 
#### Relational Databases (CPSC 304)
- Overview of database systems 
- Logical database design and normalization
- Relational algebra
- Datalog
- SQL
- Data warehousing
- Data mining
- Information retrieval
- Entity-relationship model
- Java + SQL programming project

**Textbook**: Ramakrishnan, Gehrke. Database Management Systems

**Programming Language**: SQL, Java

#### Internet Computing (CPSC 317) 
- Basic communication protocols
	- Application layer: DHCP, DNS, FTP, BGP, SMTP, POP3
	- Transport layer: TCP, UDP
	- Network layer: IP
	- Link layer: ARP
- Application layer
	- Socket programming with TCP, UDP
	- DNS resolvers
- Tranport layer
	- Multiplexing and demultiplexing
	- Principles of reliable data transfer (Go-Back-N, selective repeat)
	- Conjestion control
- Network layer
	- routers
	- Network address translation
- Link layer
	- Error-detection and error-correction techniques
- Security in computer networks
	- cryptography
	- VPNs
	- firewalls
- Principles associated with developing distributed applications

**Textbook**: Kurose, Ross. Computer Networking, A Top Down Approach

**Programming Language**: Java, C

#### Computer Hardware and Operating Systems (CPSC 313)
- Instruction set architecture and a sequential CPU
- A pipelined CPU
- The memory hierarchy
- File systems
- Virtual memory

**Programming Language**: Bryany, O'Hallaron. Computer Systems, A Programmer's Perspective

****Textbook****: C

#### Artificial Intelligence (CPSC 322)
- Reasoning and representation
- Uninformed and heuristic search methods
- Constraint satisfaction problems 
- Supervised learning
- Reasoning under uncertainty
- Planning under uncertainty
- Multiagent systems

**Textbook**: Poole, Mackworth. Artificial Intelligence, Foundations of Computational Agents

**Programming Language**: Java

#### Machine Learning and Data Mining (CPSC 340)
- Cross validation
- Decision trees
- Naive Bayes
- K-nearest-neighbours (KNN)
- Random forests
- K-means
- Linear regression
- Nonlinear regression
- Logistic regression
- Regularized regression
- Maximum likelihood estimation
- Principle component analysis (PCA)
- PageRank
- Gradient descent
- Stochastic gradient descent
- Neural networks
- Dimensionality reduction 
- Applications to computer graphics, computer games, bio-informatics, information retrieval, e-commerce, databases, computer vision and artificial intelligence

**Textbook**: Hastie, Tibshirani, Friedman. The Elements of Statistical Learning, Data Mining, Inference, and Prediction

**Programming Language**: MATLAB

#### Programming Languages
- Python 
- Java
- C/C++
- MATLAB
- Javascript
- R
- SQL