class LRUCache{
 constructor(capacity){
  this.capacity = capacity;
  this.cache-=new Map();
}
get(key){
 if(this.cache.has(key)){
 this.cache.delete(key);
 this.cache.set(key, value);
 return value;
}
return null;
}
has(key){
 if (this.cache.has(key)){
  this.cache.delete(key);
  }else if (this.cache.size>=this.capacity){
  this.cache.delete(this.cache.keys().next().value);
  }
}
function ssmiNodeTo(node){
let text=";
if(node.nodeType===Node.TEXT_NODE){
 text+=ssmiNodeToText(child);
 }
}

return text;
}
  
