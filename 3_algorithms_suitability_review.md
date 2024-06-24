<h2>3.0 Algorithm Suitability Review</h2>

<h3>Sorting</h3>
  <ol>
    <li>Strengths:
      <ul>
        <li>Optimize delivery order based on distance, time windows, and food sensitivity.</li>
        <li>Prioritize deliveries to minimize time and ensure prompt delivery of temperature-sensitive items.</li>
      </ul>
    </li>
    <li>Weaknesses:
      <ul>
        <li>Limited focus on order optimization, lacks real-time monitoring, quality control, and customer feedback considerations.</li>
      </ul>
    </li>
  </ol>

  <h3>Divide and Conquer (DAC)</h3>
  <ol>
    <li>Strengths:
      <ul>
        <li>Breaks down complex delivery processes into smaller, manageable problems for optimization.</li>
        <li>Applicable to route optimization, delivery grouping, and addressing specific challenges efficiently.</li>
      </ul>
    </li>
    <li>Weaknesses:
      <ul>
        <li>May not directly address compromised food quality unless combined with real-time monitoring, quality control, or driver guidelines.</li>
      </ul>
    </li>
  </ol>

  <h3>Dynamic Programming (DP)</h3>
  <ol>
    <li>Strengths:
      <ul>
        <li>Optimizes decisions made during the delivery process.</li>
        <li>Suitable for problems with overlapping subproblems and optimal substructure.</li>
        <li>Finds efficient routes considering distance, time windows, and food sensitivity to minimize delivery time and prioritize sensitive items.</li>
      </ul>
    </li>
    <li>Weaknesses:
      <ul>
        <li>High computational complexity for large-scale deliveries and numerous constraints.</li>
        <li>Requires extensive problem modeling and dynamic state transitions, making implementation and maintenance challenging.</li>
      </ul>
    </li>
  </ol>

  <h3>Greedy Algorithms</h3>
  <ol>
    <li>Strengths:
      <ul>
        <li>Simple, intuitive, and easy to understand and implement.</li>
        <li>Suitable for optimizing immediate route decisions or order assignments.</li>
      </ul>
    </li>
    <li>Weaknesses:
      <ul>
        <li>May not lead to optimal solutions due to focusing on locally optimal choices.</li>
        <li>Might overlook food sensitivity or real-time monitoring, impacting overall food quality.</li>
      </ul>
    </li>
  </ol>

  <h3>Graph Algorithms</h3>
  <ol>
    <li>Strengths:
      <ul>
        <li>Optimize delivery routes and prioritize time-sensitive deliveries (Dijkstra's algorithm, A* search).</li>
        <li>Consider factors like distance, traffic, and time windows to minimize delivery time and maintain food quality.</li>
        <li>Efficiently find shortest or fastest routes.</li>
      </ul>
    </li>
    <li>Weaknesses:
      <ul>
        <li>Require complex and time-consuming network modeling and data representation.</li>
        <li>May not directly address real-time monitoring, quality control, or customer feedback unless integrated with other strategies.</li>
      </ul>
    </li>
  </ol>
