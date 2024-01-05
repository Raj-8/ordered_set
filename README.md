# ordered_set

#include <iostream> 
using namespace std; 
#include <ext/pb_ds/assoc_container.hpp> 
#include <ext/pb_ds/tree_policy.hpp> 
using namespace __gnu_pbds; 
 //<--- WE CAN CHANGE THE DATA TYPE IN THE SET BELOW , AS PER OUR REQUIREMENTS ----> //
#define ordered_set tree<int, null_type,less<int>, rb_tree_tag,tree_order_statistics_node_update> 
 
// Driver program to test above functions 
int main() 
{ 
int t;cin>>t;
while(t--){
	ordered_set o_set; 

 
}
 
	return 0; 
} 
