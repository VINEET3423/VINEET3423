Compiled from "JTextComponent.java"
public abstract class javax.swing.text.JTextComponent extends javax.swing.JComponent implements javax.swing.Scrollable,javax.accessibility.Accessible{
 public static final java.lang.String FOCUS_ACCELERATOR_KEY;

    public static final java.lang.String DEFAULT_KEYMAP;

    public javax.swing.text.JTextComponent();

    public javax.swing.plaf.TextUI getUI();

    public void setUI(javax.swing.plaf.TextUI);

    public void updateUI();

    public void addCaretListener(javax.swing.event.CaretListener);

    public void removeCaretListener(javax.swing.event.CaretListener);

    public javax.swing.event.CaretListener[] getCaretListeners();

    protected void fireCaretUpdate(javax.swing.event.CaretEvent);

    public void setDocument(javax.swing.text.Document);

    public javax.swing.text.Document getDocument();

    public void setComponentOrientation(java.awt.ComponentOrientation);

    public javax.swing.Action[] getActions();

    public void setMargin(java.awt.Insets);

    public java.awt.Insets getMargin();

    public void setNavigationFilter(javax.swing.text.NavigationFilter);

    public javax.swing.text.NavigationFilter getNavigationFilter();

    public javax.swing.text.Caret getCaret();

    public void setCaret(javax.swing.text.Caret);

    public javax.swing.text.Highlighter getHighlighter();

    public void setHighlighter(javax.swing.text.Highlighter);

    public void setKeymap(javax.swing.text.Keymap);

    public void setDragEnabled(boolean);

    public boolean getDragEnabled();

    void updateInputMap(javax.swing.text.Keymap, javax.swing.text.Keymap);

    public javax.swing.text.Keymap getKeymap();

    public static javax.swing.text.Keymap addKeymap(java.lang.String, javax.swing.text.Keymap);

    public static javax.swing.text.Keymap removeKeymap(java.lang.String);

    public static javax.swing.text.Keymap getKeymap(java.lang.String);

    public static void loadKeymap(javax.swing.text.Keymap, javax.swing.text.JTextComponent$KeyBinding[], javax.swing.Action[]);

    public java.awt.Color getCaretColor();

    public void setCaretColor(java.awt.Color);

    public java.awt.Color getSelectionColor();

    public void setSelectionColor(java.awt.Color);

    public java.awt.Color getSelectedTextColor();

    public void setSelectedTextColor(java.awt.Color);

    public java.awt.Color getDisabledTextColor();

    public void setDisabledTextColor(java.awt.Color);

    public void replaceSelection(java.lang.String);

    public java.lang.String getText(int, int)       throws javax.swing.text.BadLocationException;

    public java.awt.Rectangle modelToView(int)       throws javax.swing.text.BadLocationException;

    public int viewToModel(java.awt.Point);

    public void cut();

    public void copy();

    public void paste();

    public void moveCaretPosition(int);

    public void setFocusAccelerator(char);

    public char getFocusAccelerator();

    public void read(java.io.Reader, java.lang.Object)       throws java.io.IOException;

    public void write(java.io.Writer)       throws java.io.IOException;

    public void removeNotify();

    public void setCaretPosition(int);

    public int getCaretPosition();

    public void setText(java.lang.String);

    public java.lang.String getText();

    public java.lang.String getSelectedText();

    public boolean isEditable();

    public void setEditable(boolean);

    public int getSelectionStart();

    public void setSelectionStart(int);

    public int getSelectionEnd();

    public void setSelectionEnd(int);

    public void select(int, int);

    public void selectAll();

    public java.lang.String getToolTipText(java.awt.event.MouseEvent);

    public java.awt.Dimension getPreferredScrollableViewportSize();

    public int getScrollableUnitIncrement(java.awt.Rectangle, int, int);

    public int getScrollableBlockIncrement(java.awt.Rectangle, int, int);

    public boolean getScrollableTracksViewportWidth();

    public boolean getScrollableTracksViewportHeight();

    public javax.accessibility.AccessibleContext getAccessibleContext();

    protected java.lang.String paramString();

    static final javax.swing.text.JTextComponent getFocusedComponent();

    protected void processInputMethodEvent(java.awt.event.InputMethodEvent);

    public java.awt.im.InputMethodRequests getInputMethodRequests();

    public void addInputMethodListener(java.awt.event.InputMethodListener);

    boolean composedTextExists();

    static javax.swing.text.Document access$000(javax.swing.text.JTextComponent);

    static boolean access$200(javax.swing.text.JTextComponent, int);

    static void access$300(javax.swing.text.JTextComponent);

    static int access$400(javax.swing.text.JTextComponent);

    static java.lang.Object access$500();

    static javax.swing.text.Position access$600(javax.swing.text.JTextComponent);

    static javax.swing.text.Position access$700(javax.swing.text.JTextComponent);

    static javax.swing.text.Position access$800(javax.swing.text.JTextComponent);

    static javax.swing.text.Position access$900(javax.swing.text.JTextComponent);

    static java.lang.String access$1000(javax.swing.text.JTextComponent);

    static javax.swing.text.SimpleAttributeSet access$1100(javax.swing.text.JTextComponent);

    static javax.swing.text.Position access$602(javax.swing.text.JTextComponent, javax.swing.text.Position);

    static javax.swing.text.Position access$702(javax.swing.text.JTextComponent, javax.swing.text.Position);

    static java.lang.Boolean access$1200(java.lang.Class);

    static {};

}





