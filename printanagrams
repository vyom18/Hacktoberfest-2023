class Solution {
    public List<List<String>> Anagrams(String[] string_list) {
        // Code here
        List<List<String>> res=new ArrayList<>();
        HashMap<String,List<String>> hm=new HashMap<>();
        for(String s:string_list)
        {
            char c[]=s.toCharArray();
            Arrays.sort(c);
            String str=new String(c);
            if(!hm.containsKey(str)){
hm.put(str,new ArrayList<>());
}
hm.get(str).add(s);
}
            res.addAll(hm.values());
return res;
        
    }
}
