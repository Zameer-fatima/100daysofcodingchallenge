Solution:
class Solution {
    public int[] finalPrices(int[] prices) {
        Stack<Integer> s = new Stack<>();
        for (int i = 0; i < prices.length; i++) {
            while (!s.isEmpty() && prices[s.peek()] >= prices[i])
                prices[s.pop()] -= prices[i];
            s.push(i);
        }
        return prices;
    }
}
