#ifndef LIST_H
#define LIST_H
using namespace std;
template <typename T>
class List {
    private:
        vector<T> data; 
	public:
		void insert(int pos, T e){
			if(pos<0 || pos> size()){
				throw out_of_range("La posición esta fuera del rango valido.");
			}
			data.insert(data.begin() + pos, e);
		}


        void append(T e) {
           data.push_back(e);
		}



        void prepend(T e){
			data.insert(data.begin(), e);
		}
             T remove(int pos){
			   if (pos < 0 || pos >= data.size()) {
                throw out_of_range("La posición está fuera del rango válido.");
          }
          T removedElement = data[pos];
          data.erase(data.begin() + pos);
          return removedElement;
		}
      


        T get(int pos){


		}





        int search(T e){

		}
        bool empty(){
			
		}
        int size(){
		}
}
        
        
        

        
			
