Solution:

class Solution {
    
    public int countStudents(int[] students, int[] sandwiches) {    
        LinkedList<Integer> studentQueue = new LinkedList<>();
        int len = students.length;
        for (int i = 0; i < len; i++) {
            studentQueue.offer(i);
        }
        
        int lastQuery = -1;
        int sIdx = 0;
        
        while (sIdx < len) {
            if (studentQueue.peekFirst() == lastQuery) {
                break;
            } else if (students[studentQueue.peekFirst()] == sandwiches[sIdx]) {
                studentQueue.pollFirst();
                lastQuery = -1;
                sIdx++;
            } else {
                Integer tmp = studentQueue.pollFirst();
                studentQueue.offer(tmp);
                if (lastQuery == -1) {
                    lastQuery = tmp;
                }
            }
        }        
        
        return studentQueue.size();
    }
}
