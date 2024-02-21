---
titulo: Widget TextView
---
- [Widget TextView no Android usando Java com exemplos](https://acervolima.com/widget-textview-no-android-usando-java-com-exemplos/): Widget refere-se aos elementos da IU (Interface do usuário) que ajuda o usuário a interagir com o aplicativo Android. TextView é um dos muitos widgets que podem ser usados ​​para melhorar a interface do usuário do aplicativo.

# Widget TextView

- **Widget** refere-se aos elementos da interface do usuário que ajuda o usuário a interagir com o aplicativo Android.
- **TextView** refere-se ao widget que exibe algum texto na tela com base no layout, tamanho, cor etc. definido para aquele TextView específico. Opcionalmente, também nos permite modificar ou editar a si mesmo.

## Exemplo de código

~~~java
package com.project.textview;
  
import androidx.appcompat.app.AppCompatActivity;
import android.os.Bundle;
import android.view.View;
import android.widget.TextView;
import android.widget.Toast;
  
public class MainActivity extends AppCompatActivity {
  
    // Creating the instance of the TextView created
    private TextView textView;
  
    @Override
    protected void onCreate(Bundle savedInstanceState)
    {
        super.onCreate(savedInstanceState);
  
        // Linking the activity file to this Java file
        setContentView(R.layout.activity_main);
  
        // Get the TextView with the id
        // mentioned in the layout file
        textView = (TextView)findViewById(R.id.textview);
  
        // Try to change the text of the Textview upon touch
        // and also display a Toast message
        textView.setOnClickListener(new View.OnClickListener() {
  
            @Override
            public void onClick(View v)
            {
  
                // Changing text
                textView.setText("GeeksforGeeks");
  
                // Displaying Toast message
                Toast
                    .makeText(MainActivity.this,
                              "Welcome to GeeksforGeeks",
                              Toast.LENGTH_SHORT)
                    .show();
            }
        });
    }
}
~~~java
