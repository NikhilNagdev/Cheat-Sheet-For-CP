## In order to fill the list with a repeated object alternatively you can use
`ArrayList<Integer> arr=new ArrayList<Integer>(Collections.nCopies(10, 0));`

## To iterate over a map
    for (Map.Entry<String, Object> entry : map.entrySet()) {
      String key = entry.getKey();
      Object value = entry.getValue();
    }
