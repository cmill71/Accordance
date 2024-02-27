# Accordance
//This app was designed or a school course only. My exptertise in the field is very limited, but it was a fun project either way!

//
//  ContentView.swift
//  Accordance1.0
//
//  Created by Corey Miller on 2/25/24.
//

import SwiftUI

struct ContentView: View {
  var body: some View {
    VStack(spacing: 50) {
      Text("Accordance")
            .font(.system(size: 60))
        .fontWeight(.bold)
        .fontDesign(.monospaced)
        .padding(.bottom, 20)
           
      /* Solid Button */
      Button(action: {}) {
        Text("Chat 1")
              .font(.system(size: 30))
          .padding(25)
          .frame(width: 1000)
          .foregroundColor(.white)
          .background(.orange)
          .cornerRadius(10)
      }
        Button(action: {}) {
            Text("Chat 2")
                .font(.system(size: 30))
                .padding(25)
                .frame(width: 1000)
                .foregroundColor(.white)
                .background(.orange)
                .cornerRadius(10)
        }
        Button(action: {}) {
            Text("Chat 3")
                .font(.system(size: 30))
                .padding(25)
                .frame(width: 1000)
                .foregroundColor(.white)
                .background(.orange)
                .cornerRadius(10)
        }
        Button(action: {}) {
            Text("Chat 4")
                .font(.system(size: 30))
                .padding(25)
                .frame(width: 1000)
                .foregroundColor(.white)
                .background(.orange)
                .cornerRadius(10)
        }
      }
    }
  }
    
    
    struct ContenView_Previews: PreviewProvider {
            static var previews: some View {
                ContentView()
            }
        }
    
   

