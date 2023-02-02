# get_next_line

  <h2>:star2: About The Project</h2>
  <p>
   The goal of the project is to create a script that receives a file descriptor and reads a predefined amount of bytes <em>BUFFER_SIZE</me>, until the end of a line is reached. When the number of bytes in the line is not a multiple of <em>BUFFER_SIZE</me>, the read function will read bytes that do not belong to the line in question, but to the next line. As a result, this project reads and returns one line at a time from a file descriptor, whenever the get_next_line function is executed.
  The bonus part handles multiple text files simultaneously.
  </p>
</div>

<div>
  <h2>:dart: Table of Contents</h2>
  <li>Mandatory Part One</li>
  </br>
  <ul>
  <details>
    <summary>get_next_line.c</summary>
    <p>Checks and reads the contents of the file descriptor to the end of the line one line at a time.</p>
    </details>
  <details>
    <summary>get_next_line.h</summary>
    <p>Header of the project</p>
    </details>
  <details>
    <summary>get_next_line_utils.c</summary>
    <p>General purpose functions. Check out the individual documentation <a href="https://github.com/knoxvillie/libft" target="_blank">here.</a></p>
    </details>
  </ul>

  </br>
