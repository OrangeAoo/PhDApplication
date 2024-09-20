<head>
  <!-- MathJax CDN -->
  <script src="https://cdn.jsdelivr.net/npm/mathjax@3/es5/tex-mml-chtml.js"></script>
</head>

<body>
  <h1 style="margin: auto; line-height: 50px"> <center>Principle-Agent Mean Field Game In Renewable Energy Certificate Markets</center> </h1>
  <h1 style="margin: auto; line-height: 60px"> <center>(PA-MFG in REC Markets)</center> </h1>
  <p style="line-height: 1.5; font-family: Calibri">
  Conventional numerical solvers are hard pressed to solve PA-MFG with market-clearing conditions, which may be faced with the "curse of dimentionality". Thus in their study <a href="https://doi.org/10.48550/arXiv.2110.01127" style="color: pink; text-decoration: underline;"> [1]</a>, Professor Campbell and his fellows proposed an actor-critic approach to optimization, where the agents form a Nash equilibria according to the principal’s penalty function, and the principal evaluates the resulting equilibria. And they applies this approach to a stylized PA problem arising in Renewable Energy Certificate (REC) markets, where agents may <i>work</i> overtime (or <i>rent</i> capacity), <i>trade</i> RECs, and <i>expand</i> their long-term capacity to navigate the market at maximum profit.
  </p>

  <p style='line-height: 1.5; font-family: Calibri'>
  And beyond the origianl study, in the summer of 2024, we further complicated the topic, i.e. extending from 1-period scenario to 2-period scenarios, providing insteresting insights into how "planning ahead" would make a difference in the agents' performance and the markets. 
  </p>

  <p style="line-height: 1.5; font-family: Calibri;">
  In this report, we will go throgh the following parts, yet with more weights put on the extended topic (<code>part 4</code>).
  </p>

  <blockquote style="border-left: 4px solid #ccc; padding-left: 0px; margin-left: 0; font-family: Calibri; line-height: 2">
    <ul style="list-style-type: disc;">
      <li> <code>Part 1</code> FBSDE: Modeling of The PA Problem in REC Markets </li>
      <li> <code>Part 2</code> Multi-Step NN Solver: Single Agent Market in Single Period</li>
      <ul style="list-style-type: circle; padding-left: 65px;">
          <li> A Simply Example: Smooth Penalty Function \(g(\cdot)\) </li>
          <li> Approximation by Linear Combos of Call/Put Functions And Tricks: Improve The Numerical Stability And Convergency </li> 
      </ul>
      <li> <code>Part 3</code> 2(multi)-Agent Market in Single Period </li>
      <li> <code>Part 4</code> 2(multi)-Agent Market in 2(multi)-Period </li> 
      <ul style="list-style-type: circle; padding-left: 65px;">
        <li> Jointly Optimization: Plan Ahead </li>
        <li> Separate Optimization: Care Present Only </li>
        <li> Comparison: Long/Short-Sighted Performances And Market Impacts
    </ul>
  </blockquote>

</body>

