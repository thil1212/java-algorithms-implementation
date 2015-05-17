# Introduction #
This is a collection of algorithms and data structures which I've implement over the years in my academic and professional life. The code isn't overly-optimized but is written to be correct and readable. The algorithms and data structures are well tested and, unless noted, are believe to be 100% correct. All code is Java 1.6 compliant and was tested on a Intel Core 2 Duo Processor which has 2.0 GHz per core and 2 Gbytes of memory. The following VM Arguments were used: "-server -Xms1500m -Xmx1500m".

_Created by Justin Wetherell_<br>
Google: <a href='http://code.google.com/p/java-algorithms-implementation'>http://code.google.com/p/java-algorithms-implementation</a><br>
Github: <a href='http://github.com/phishman3579/java-algorithms-implementation'>http://github.com/phishman3579/java-algorithms-implementation</a><br>
<code>LinkedIn</code>: <a href='http://www.linkedin.com/in/phishman3579'>http://www.linkedin.com/in/phishman3579</a><br>
E-mail: <a href='mailto:phishman3579@gmail.com'>mailto:phishman3579@gmail.com</a><br>
Twitter: <a href='https://twitter.com/phishman3579'>https://twitter.com/phishman3579</a><br>

<h1>What's been implemented:</h1>

<h2>Data Structures</h2>
<ul><li>AVL Tree<br>
</li><li>B-Tree<br>
</li><li>Binary Heap <code>[backed by an array or a tree]</code>
</li><li>Binary Search Tree<br>
</li><li>Compact Suffix Trie <code>[backed by a Patricia Trie]</code>
</li><li>Graph<br>
<ul><li>Undirected<br>
</li><li>Directed (Digraph)<br>
</li></ul></li><li>Hash Array Mapped Trie (HAMT)<br>
</li><li>Hash Map (associative array)<br>
</li><li>Interval Tree<br>
</li><li>KD Tree (k-dimensional tree or k-d tree)<br>
</li><li>List <code>[backed by an array or a linked list]</code>
</li><li>Matrix<br>
</li><li>Patricia Trie<br>
</li><li>Quad-Tree (Point-Region or MX-CIF)<br>
</li><li>Queue <code>[backed by an array or a linked list]</code>
</li><li>Radix Trie (associative array) <code>[backed by a Patricia Trie]</code>
</li><li>Red-Black Tree<br>
</li><li>Segment Tree<br>
</li><li>Skip List<br>
</li><li>Splay Tree<br>
</li><li>Stack <code>[backed by an array or a linked list]</code>
</li><li>Suffix Tree (Ukkonen's algorithm)<br>
</li><li>Suffix Trie <code>[backed by a Trie]</code>
</li><li>Treap<br>
</li><li>Tree Map (associative array) <code>[backed by an AVL Tree]</code>
</li><li>Trie<br>
</li><li>Trie Map (associative array) <code>[backed by a Trie]</code></li></ul>

<h2>Mathematics</h2>
<ul><li>Distance<br>
<ul><li>chebyshev<br>
</li><li>euclidean<br>
</li></ul></li><li>Division<br>
<ul><li>using a loop<br>
</li><li>using recursion<br>
</li><li>using shifts and multiplication<br>
</li><li>using only shifts<br>
</li><li>using logarithm<br>
</li></ul></li><li>Multiplication<br>
<ul><li>using a loop<br>
</li><li>using recursion<br>
</li><li>using only shifts<br>
</li><li>using logarithms<br>
</li></ul></li><li>Primes<br>
<ul><li>is prime<br>
</li><li>prime factorization<br>
</li><li>sieve of eratosthenes</li></ul></li></ul>

<h2>Numbers</h2>
<ul><li>Integers<br>
<ul><li>to binary String<br>
<ul><li>using divide and modulus<br>
</li><li>using right shift and modulus<br>
</li><li>using <code>BigDecimal</code>
</li><li>using divide and double<br>
</li></ul></li><li>is a power of 2<br>
<ul><li>using a loop<br>
</li><li>using recursion<br>
</li><li>using logarithm<br>
</li><li>using bits<br>
</li></ul></li><li>greatest common divisor<br>
<ul><li>using Euclid's algorithm<br>
</li></ul></li><li>to English (e.g. 1 would return "one")<br>
</li></ul></li><li>Longs<br>
<ul><li>to binary String<br>
<ul><li>using divide and modulus<br>
</li><li>using right shift and modulus<br>
</li><li>using <code>BigDecimal</code></li></ul></li></ul></li></ul>

<h2>Path</h2>
<ul><li>Find shortest path(s) in a Graph from a starting Vertex<br>
<ul><li>Dijkstra's algorithm (non-negative weight graphs)<br>
</li><li>Bellman-Ford algorithm (negative and positive weight graphs)<br>
</li></ul></li><li>Find minimum spanning tree<br>
<ul><li>Prim's (undirected graphs)<br>
</li></ul></li><li>Find all pairs shortest path<br>
<ul><li>Johnsons's algorithm (negative and positive weight graphs)<br>
</li><li>Floyd-Warshall (negative and positive weight graphs)<br>
</li></ul></li><li>Cycle detection<br>
<ul><li>Depth first search while keeping track of visited Verticies<br>
</li></ul></li><li>Topological sort</li></ul>

<h2>Search</h2>
<ul><li>Get index of value in array<br>
<ul><li>Linear<br>
</li><li>Quickselect<br>
</li><li>Binary <code>[sorted array input only]</code>
</li><li>Optimized binary (binary until a threashold then linear) <code>[sorted array input only]</code>
</li><li>Interpolation <code>[sorted array input only]</code></li></ul></li></ul>

<h2>Sequences</h2>
<ul><li>Find longest common subsequence (dynamic programming)<br>
</li><li>Find number of times a subsequence occurs in a sequence (dynamic programming)<br>
</li><li>Find i-th element in a Fibonacci sequence<br>
<ul><li>using a loop<br>
</li><li>using recursion<br>
</li><li>using matrix multiplication<br>
</li><li>using Binet's formula<br>
</li></ul></li><li>Find total of all elements in a sequence<br>
<ul><li>using a loop<br>
</li><li>using Triangular numbers</li></ul></li></ul>

<h2>Sorts</h2>
<ul><li>American Flag Sort<br>
</li><li>Bubble Sort<br>
</li><li>Counting Sort (Integers only)<br>
</li><li>Heap Sort<br>
</li><li>Insertion Sort<br>
</li><li>Merge Sort<br>
</li><li>Quick Sort<br>
</li><li>Radix Sort (Integers only)<br>
</li><li>Shell's Sort</li></ul>

<h2>String Functions</h2>
<ul><li>Reverse characters in a string<br>
<ul><li>using additional storage (a <code>String</code> or <code>StringBuilder</code>)<br>
</li><li>using in-place swaps<br>
</li><li>using in-place XOR<br>
</li></ul></li><li>Reverse words in a string<br>
<ul><li>using char swaps and additional storage (a <code>StringBuilder</code>)<br>
</li><li>using <code>StringTokenizer</code> and additional (a <code>String</code>)<br>
</li><li>using split() method and additional storage (a <code>StringBuilder</code> and <code>String[]</code>)<br>
</li><li>using in-place swaps<br>
</li></ul></li><li>Is Palindrome<br>
<ul><li>using additional storage (a <code>StringBuilder</code>)<br>
</li><li>using in-place symetric element compares<br>
</li></ul></li><li>Subsets of characters in a String<br>
</li><li>Edit (Levenshtein) Distance of two Strings</li></ul>

<h3>Sorted Data Structure run-time comparison [100,000 items]</h3>
<table><thead><th>Data Structure          </th><th>Add random items  </th><th>Remove random items  </th><th>Add sorted items  </th><th>Remove sorted items	</th><th>Look-up time  </th><th>Size</th></thead><tbody>
<tr><td>AVL Tree                </td><td>67.33 ms          </td><td>58.33 ms             </td><td>37.33 ms          </td><td>23.67 ms             </td><td>5.67 ms       </td><td>4.8 MB</td></tr>
<tr><td>B-Tree                  </td><td>174.33 ms         </td><td>69.33 ms             </td><td>39.33 ms          </td><td>29.67 ms             </td><td>6.67 ms       </td><td>5.06 MB</td></tr>
<tr><td>Binary Search Tree      </td><td>42.33 ms          </td><td>39.67 ms             </td><td>15.86 s           </td><td>17.27 s              </td><td>5.79 s        </td><td>4.8 MB</td></tr>
<tr><td>Min-Heap <code>[array]</code>      </td><td>53.67 ms          </td><td>48 ms                </td><td>50.67 ms          </td><td>37.33 ms             </td><td>1.58 s        </td><td>1.97 MB</td></tr>
<tr><td>Min-Heap <code>[tree]</code>       </td><td>44.67 ms          </td><td>82.67 ms             </td><td>42 ms             </td><td>54.67 ms             </td><td>5.49 s        </td><td>4.8 MB</td></tr>
<tr><td>Java's Min-Heap         </td><td>13.33 ms          </td><td>27 ms                </td><td>10.67 ms          </td><td>17.33 ms             </td><td>1.74 s        </td><td>1.78 MB</td></tr>
<tr><td>Max-Heap <code>[array]</code>      </td><td>52.33 ms          </td><td>50.67 ms             </td><td>79.33 ms          </td><td>35 ms                </td><td>1.58 s        </td><td>2 MB</td></tr>
<tr><td>Max-Heap <code>[tree]</code>       </td><td>41.33 ms          </td><td>78.33 ms             </td><td>54.67 ms          </td><td>50.33 ms             </td><td>5.48 s        </td><td>4.8 MB</td></tr>
<tr><td>Java's Max-Heap         </td><td>12.67 ms          </td><td>30.33 ms             </td><td>14.67 ms          </td><td>19.33 ms             </td><td>1.62 s        </td><td>1.72 MB</td></tr>
<tr><td>Patricia Trie           </td><td>130.33 ms         </td><td>75 ms                </td><td>44 ms             </td><td>33.67 ms             </td><td>9.33 ms       </td><td>12.23 MB</td></tr>
<tr><td>Red-Black Tree          </td><td>52 ms             </td><td>49.67 ms             </td><td>32 ms             </td><td>13.67 ms             </td><td>7 ms          </td><td>8 MB</td></tr>
<tr><td>Java's Red-Black Tree   </td><td>45.33 ms          </td><td>38 ms                </td><td>26 ms             </td><td>10 ms                </td><td>4.67 ms       </td><td>5.6 MB</td></tr>
<tr><td>Skip List               </td><td>96 ms             </td><td>69 ms                </td><td>69 ms             </td><td>24 ms                </td><td>93 ms         </td><td>3.47 MB</td></tr>
<tr><td>Java's Skip List        </td><td>102 ms            </td><td>99 ms                </td><td>57 ms             </td><td>41 ms                </td><td>73 ms         </td><td>3.59 MB</td></tr>
<tr><td>Splay Tree              </td><td>65.67 ms          </td><td>64 ms                </td><td>14.67 ms          </td><td>7 ms                 </td><td>5.67 ms       </td><td>4.8 MB</td></tr>
<tr><td>Treap                   </td><td>53 ms             </td><td>37.33 ms             </td><td>19.67 ms          </td><td>11.67 ms             </td><td>7.33 ms       </td><td>4.8 MB</td></tr>
<tr><td>Trie                    </td><td>57.33 ms          </td><td>59.33 ms             </td><td>27 ms             </td><td>27 ms                </td><td>13.67 ms      </td><td>20.51 MB</td></tr></tbody></table>

<h3>Unsorted Data Structure run-time comparison [100,000 items]</h3>
<table><thead><th>Data Structure          </th><th>Add random items  </th><th>Remove random items  </th><th>Add sorted items  </th><th>Remove sorted items	</th><th>Look-up time  </th><th>Size</th></thead><tbody>
<tr><td>List <code>[array]</code>          </td><td>16 ms             </td><td>4.18 s               </td><td>13 ms             </td><td>4.77 s               </td><td>1.66 s        </td><td>1.99 MB</td></tr>
<tr><td>Java's List <code>[array]</code>   </td><td>10 ms             </td><td>3.3 s                </td><td>9.33 ms           </td><td>6.15 s               </td><td>2.2 s         </td><td>1.78 MB</td></tr>
<tr><td>List <code>[linked]</code>         </td><td>10.67 ms          </td><td>10.81 s              </td><td>11 ms             </td><td>21.61 s              </td><td>7.25 s        </td><td>4 MB</td></tr>
<tr><td>Java's List <code>[linked]</code>  </td><td>10.33 ms          </td><td>10.83 s              </td><td>11 ms             </td><td>22.01 s              </td><td>6.82 s        </td><td>4 MB</td></tr>
<tr><td>Queue <code>[array]</code>         </td><td>18 ms             </td><td>6 ms                 </td><td>15 ms             </td><td>6 ms                 </td><td>1.88 s        </td><td>1.97 MB</td></tr>
<tr><td>Java's Queue <code>[array]</code>  </td><td>11.67 ms          </td><td>1.67 ms              </td><td>7.67 ms           </td><td>1.67 ms              </td><td>3.79 s        </td><td>1.77 MB</td></tr>
<tr><td>Queue <code>[linked]</code>        </td><td>10.33 ms          </td><td>3.33 ms              </td><td>10.67 ms          </td><td>3 ms                 </td><td>7.2 s         </td><td>4 MB</td></tr>
<tr><td>Java's Queue <code>[linked]</code> </td><td>9 ms              </td><td>2.33 ms              </td><td>10 ms             </td><td>2 ms                 </td><td>6.75 s        </td><td>3.94 MB</td></tr>
<tr><td>Stack <code>[array]</code>         </td><td>14.67 ms          </td><td>6.33 ms              </td><td>15.67 ms          </td><td>6.33 ms              </td><td>1.68 s        </td><td>1.97 MB</td></tr>
<tr><td>Stack <code>[linked]</code>        </td><td>11 ms             </td><td>3.33 ms              </td><td>11.67 ms          </td><td>3 ms                 </td><td>5.06 s        </td><td>4 MB</td></tr>
<tr><td>Java's Stack <code>[vector]</code> </td><td>12.33 ms          </td><td>7.33 ms              </td><td>9.67 ms           </td><td>4.33 ms              </td><td>1.63 s        </td><td>1.82 MB</td></tr></tbody></table>

<h3>Map Data Structure run-time comparison [100,000 items]</h3>
<table><thead><th>Data Structure          </th><th>Add random items  </th><th>Remove random items  </th><th>Add sorted items  </th><th>Remove sorted items	</th><th>Look-up time  </th><th>Size</th></thead><tbody>
<tr><td>Hash Map                </td><td>46.33 ms          </td><td>22 ms                </td><td>52.67 ms          </td><td>35.67 ms             </td><td>44 ms         </td><td>7.23 MB</td></tr>
<tr><td>Java's Hash Map         </td><td>32.67 ms          </td><td>16.33 ms             </td><td>31.33 ms          </td><td>17 ms                </td><td>15.67 ms      </td><td>8.19 MB</td></tr>
<tr><td>Radix Trie              </td><td>212 ms            </td><td>130.33 ms            </td><td>170.33 ms         </td><td>88.67 ms             </td><td>86.67 ms      </td><td>11.02 MB</td></tr>
<tr><td>Tree Map                </td><td>113.67 ms         </td><td>90.33 ms             </td><td>71.33 ms          </td><td>46 ms                </td><td>55.67 ms      </td><td>8.79 MB</td></tr>
<tr><td>Java's Tree Map         </td><td>89.33 ms          </td><td>88 ms                </td><td>85.33 ms          </td><td>43 ms                </td><td>77 ms         </td><td>8.79 MB</td></tr>
<tr><td>Trie Map                </td><td>111 ms            </td><td>86.67 ms             </td><td>96 ms             </td><td>62.67 ms             </td><td>84.67 ms      </td><td>20.03 MB</td></tr>
<tr><td>Java's Skip List Map    </td><td>125.33 ms         </td><td>121.67 ms            </td><td>60.33 ms          </td><td>43 ms                </td><td>85.33 ms      </td><td>9.19 MB</td></tr>
<tr><td>Skip List Map           </td><td>135.67 ms         </td><td>99.33 ms             </td><td>69.67 ms          </td><td>25.33 ms             </td><td>96.33 ms      </td><td>9.86 MB</td></tr>
<tr><td>HAMT                    </td><td>60.33 ms          </td><td>28.67 ms             </td><td>58.67 ms          </td><td>37 ms                </td><td>38 ms         </td><td>10.18 MB</td></tr></tbody></table>

<h3>Sorting Algorithm run-time comparison [100,000 items]</h3>
<table><thead><th>Algorithm				</th><th>Random	</th><th>Sorted	</th><th>Reverse Sorted</th></thead><tbody>
<tr><td>Insertion sort			</td><td>8.83		 </td><td>0.0		  </td><td>14.477        </td></tr>
<tr><td>Bubble sort				</td><td>28.741	</td><td>0.001		</td><td>12.314        </td></tr>
<tr><td>Shell sort				</td><td>1.244		</td><td>0.009		</td><td>2.156         </td></tr>
<tr><td>Merge sort				</td><td>0.072		</td><td>0.029		</td><td>0.026         </td></tr>
<tr><td>Quicksort with first as pivot		</td><td>0.142		</td><td>0.01		 </td><td>0.013         </td></tr>
<tr><td>Quicksort with middle as pivot	</td><td>0.022		</td><td>0.01		 </td><td>0.015         </td></tr>
<tr><td>Quicksort with random as pivot	</td><td>0.025		</td><td>0.014		</td><td>0.011         </td></tr>
<tr><td>Heap sort				</td><td>0.057		</td><td>0.024		</td><td>0.017         </td></tr>
<tr><td>Counting sort				</td><td>0.019		</td><td>0.001		</td><td>0.002         </td></tr>
<tr><td>Radix sort				</td><td>0.053		</td><td>0.019		</td><td>0.02          </td></tr>
<tr><td>American Flag sort			</td><td>0.056		</td><td>0.021		</td><td>0.026         </td></tr></tbody></table>

<h3>Sorting Algorithm run-time comparison [500,000 items]</h3>
<table><thead><th>Algorithm				</th><th>Random	</th><th>Sorted	</th><th>Reverse Sorted</th></thead><tbody>
<tr><td>Merge sort				</td><td>0.285		</td><td>0.088		</td><td>0.086         </td></tr>
<tr><td>Quicksort with first as pivot		</td><td>0.154		</td><td>0.053		</td><td>0.048         </td></tr>
<tr><td>Quicksort with middle as pivot	</td><td>0.121		</td><td>0.043		</td><td>0.047         </td></tr>
<tr><td>Quicksort with random as pivot	</td><td>0.121		</td><td>0.04		 </td><td>0.048         </td></tr>
<tr><td>Heap sort				</td><td>0.303		</td><td>0.133		</td><td>0.098         </td></tr>
<tr><td>Counting sort				</td><td>0.04		 </td><td>0.009		</td><td>0.007         </td></tr>
<tr><td>Radix sort				</td><td>0.146		</td><td>0.091		</td><td>0.075         </td></tr>
<tr><td>American Flag sort			</td><td>0.186		</td><td>0.121		</td><td>0.119         </td></tr></tbody></table>

<h3>Sorting Algorithm run-time comparison [1,000,000 items]</h3>
<table><thead><th>Algorithm				</th><th>Random	</th><th>Sorted	</th><th>Reverse Sorted</th></thead><tbody>
<tr><td>Merge sort				</td><td>0.682		</td><td>0.189		</td><td>0.16          </td></tr>
<tr><td>Quicksort with first as pivot		</td><td>0.315		</td><td>0.084		</td><td>0.082         </td></tr>
<tr><td>Quicksort with middle as pivot	</td><td>0.269		</td><td>0.081		</td><td>0.083         </td></tr>
<tr><td>Quicksort with random as pivot	</td><td>0.277		</td><td>0.087		</td><td>0.077         </td></tr>
<tr><td>Heap sort				</td><td>0.651		</td><td>0.281		</td><td>0.2           </td></tr>
<tr><td>Counting sort				</td><td>0.07		 </td><td>0.019		</td><td>0.013         </td></tr>
<tr><td>Radix sort				</td><td>0.246		</td><td>0.195		</td><td>0.168         </td></tr>
<tr><td>American Flag sort			</td><td>0.362		</td><td>0.24		 </td><td>0.218         </td></tr></tbody></table>

<h3>Sorting Algorithm run-time comparison [5,000,000 items]</h3>
<table><thead><th>Algorithm				</th><th>Random	</th><th>Sorted	</th><th>Reverse Sorted</th></thead><tbody>
<tr><td>Merge sort				</td><td>3.79		 </td><td>1.008		</td><td>0.892         </td></tr>
<tr><td>Quicksort with first as pivot		</td><td>1.753		</td><td>0.428		</td><td>0.425         </td></tr>
<tr><td>Quicksort with middle as pivot	</td><td>1.737		</td><td>0.419		</td><td>0.406         </td></tr>
<tr><td>Quicksort with random as pivot	</td><td>1.763		</td><td>0.437		</td><td>0.419         </td></tr>
<tr><td>Heap sort				</td><td>4.773		</td><td>1.632		</td><td>1.183         </td></tr>
<tr><td>Counting sort				</td><td>1.384		</td><td>0.078		</td><td>0.057         </td></tr>
<tr><td>Radix sort				</td><td>1.218		</td><td>1.023		</td><td>1.002         </td></tr>
<tr><td>American Flag sort			</td><td>1.838		</td><td>1.379		</td><td>1.248         </td></tr></tbody></table>

<h3>Sorting Algorithm run-time comparison [10,000,000 items]</h3>
<table><thead><th>Algorithm				</th><th>Random	</th><th>Sorted	</th><th>Reverse Sorted</th></thead><tbody>
<tr><td>Merge sort				</td><td>7.335		</td><td>2.154		</td><td>1.965         </td></tr>
<tr><td>Quicksort with first as pivot		</td><td>4.253		</td><td>1.002		</td><td>1.034         </td></tr>
<tr><td>Quicksort with middle as pivot	</td><td>4.007		</td><td>0.931		</td><td>0.868         </td></tr>
<tr><td>Quicksort with random as pivot	</td><td>4.053		</td><td>0.985		</td><td>0.877         </td></tr>
<tr><td>Heap sort				</td><td>11.246	</td><td>3.388		</td><td>2.458         </td></tr>
<tr><td>Counting sort				</td><td>0.62		 </td><td>0.148		</td><td>0.119         </td></tr>
<tr><td>Radix sort				</td><td>2.898		</td><td>3.095		</td><td>3.932         </td></tr>
<tr><td>American Flag sort			</td><td>7.464		</td><td>4.038		</td><td>3.888         </td></tr>