# Length-of-last-word-in-String
class Solution {
    public int lengthOfLastWord(String s) {
        s = s.trim();                   // remove extra spaces
        int lastSpace = s.lastIndexOf(" "); // index of last space
        return s.length() - lastSpace - 1; // length of last word
    }
}
