# H1 Preview
## H2 Preview
### H3 Preview
#### H4 Preview
##### H5 Preview
###### H6 Preview
![Image of The Rock](https://m.media-amazon.com/images/M/MV5BOWU1ODBiNGUtMzVjNi00MzdhLTk0OTktOWRiOTIxMWNhOGI2XkEyXkFqcGdeQXVyMTU2OTM5NDQw._V1_FMjpg_UX1000_.jpg)
``` javascript
package vocab;

/** -----------------------------------------------------
 *	Jeremie Beaudoin 40276582, Sammy Mohellebi 40282374
 *	Assignment 3
 *	Due April 15 2024
 *	-----------------------------------------------------
 */ 

import linkedLists.*;

/**This class stores the topics, and their words.
 * The topic is stored as a string, and the list of words
 * is stored in a linked list.
 */
public class Vocab {

	/**Stores name of the topic
	 */
	private String topic;

	/**Stores words contained under the topic
	 */
	private SinglyLinkedList words;

	/**SinglyLinkedList's iterator
	 */
	private SinglyLinkedList.ListIterator topicIterator;
	
	/**Parameterized constructor
	 * @param topic String storing the topic name
	 */
	public Vocab(String topic) {
		this.topic = topic;
		this.words = new SinglyLinkedList();
		this.topicIterator = words.iterator();
	}

	/**Getter
	 * @return topic String
	 */
	public String getTopic() {
		return topic;
	}

	/**Setter
	 * @param topic new String
	 */
	public void setTopic(String topic) {
		this.topic = topic;
	}

	/**Getter
	 * @return linked list's iterator
	 */
	public SinglyLinkedList.ListIterator getTopicIterator() {
		return topicIterator;
	}
	
	/**Overridden toString method
	 * @return topic String
	 */
	public String toString() {
		return this.topic;
	}
	
}
```
